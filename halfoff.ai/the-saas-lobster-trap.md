# The SaaS Lobster Trap: Why Your Software Bill Keeps Rising — and How Companies Are Quietly Escaping

A trap rarely looks like a trap from the outside. Think of a wire lobster trap: there's bait, the entrance is easy, and walking in gives you exactly what you wanted at that moment. It's only once you try to turn around that the design reveals itself — you can't get back out, and the water keeps getting warmer.

That's a fair description of what enterprise SaaS has become for a lot of companies. What began a decade ago as a cost-saving miracle has quietly hardened into an inescapable budget drain, with prices climbing every year on systems you can no longer live without. This article unpacks why that's happening, the escape route a growing number of finance and IT leaders are exploring — "SaaS repatriation" — and the real legal and operational catches you'd need to navigate before betting on it.

## The math that's eating IT budgets alive

Start with the macro picture, because it explains the squeeze everyone feels. Corporate IT budgets have been growing at a modest pace — on the order of a few percent a year, roughly keeping up with inflation. SaaS subscription prices, meanwhile, have been inflating much faster, with industry estimates putting average increases well into the double digits year over year.

When your budget grows ~3% but your single largest operating expense grows ~11%, you don't have a line-item problem — you have a slow-motion solvency problem. It forces an ugly internal zero-sum game: cut new projects, or cut headcount, just to keep the existing software running. Companies are, in effect, laying people off to afford their renewals.

What makes it worse is how much of that spend is pure waste. The average enterprise now juggles hundreds of separate SaaS applications, and research suggests a large share of provisioned seats — often cited at nearly half — go unused or underutilized. That's money paid for logins nobody touches.

## How vendors hide the hikes

Vendors don't send an email announcing "we're raising your price 11% because we can." They use packaging tactics that obscure the increase.

The big one right now is **AI bundling** — what one research brief memorably calls the "innovation tax." A majority of major vendors are folding generative-AI features into base plans whether you asked for them or not. Running AI models genuinely costs compute, so there's a real expense involved — but the features double as cover for raising overall platform prices, with no way to opt out. You pay for the AI regardless of whether your team uses it. It's a bit like a landlord installing a smart thermostat in a hallway you never walk through, then citing it to raise your rent.

The second tactic is the shift from transparent, flat pricing to **opaque credit systems**. Instead of buying a service, you buy a bucket of abstract tokens — and the vendor keeps the right to change how many tokens an action costs mid-contract. A report that cost one credit today can quietly cost five next month. Your headline subscription fee never moves, but your real cost per workflow climbs invisibly. You just run out of credits faster.

## Why "optimization" tools don't fix the root problem

The natural response is FinOps and SaaS-management tools, and to be fair, they work at what they do: finding shadow IT and clawing back those unused seats. But there's a structural ceiling to that approach. These tools optimize the *rent*. They cancel the leases on empty apartments — they do nothing to stop the landlord raising the price on the apartments you still need. You remain locked into the ecosystem and fully exposed to next year's hike.

If trimming the rent doesn't stop the increases, the only structural alternative is to stop renting. That's the idea behind **SaaS repatriation**: moving core workflows off closed, proprietary SaaS and onto managed open-source platforms the company actually owns. The apex target — highest friction, highest reward — is usually the CRM, the central nervous system of most sales orgs. A mid-sized CRM deployment, once you stack premium AI tiers, compounding annual renewals, and the army of certified admins needed to keep it running, can approach seven figures of total cost over five years.

## The catches nobody should gloss over

Repatriation sounds like an obvious win, which is exactly why the catches deserve honest attention. There are three.

**"Free" open source isn't free.** It's free like a free puppy. Hosting, DevOps, security patching, and uptime are expensive, and a company that simply rebuilds a CRM in-house with its own engineers will often see five-year operating costs eclipse the original licensing fees. The only version that pencils out is *managed* open source — where a provider absorbs the infrastructure, the 2 a.m. patching, and the uptime SLAs, bundling software plus labor into one predictable fee. That predictability, not the software being "free," is what caps a CFO's exposure.

**The legal frontier is real — and partly untested.** Vendor terms of service forbid reverse-engineering and competitive replication; you cannot copy a UI or lift code without inviting a crushing lawsuit. The lawful path is **clean-room engineering**, a decades-old defense rooted in *Computer Associates v. Altai* (1992), which established that copyright protects the specific *expression* of code, not the underlying *idea*. The classic analogy: one chef tastes a cake and writes detailed flavor notes; a second, isolated chef bakes a functionally identical cake from those notes alone, never seeing the original. The separation creates a defensible paper trail of independent creation. The important caveat — and the transcript is emphatic about this — is that while *human* clean-room work is well-established, doing it with automated AI agents is a legal frontier that hasn't been tested in appellate courts. Anyone going this route should demand ironclad contractual indemnification, so the provider, not your company, becomes the expensive test case if a vendor sues.

**Migration is where most attempts die.** A large majority of data-migration projects fail or blow their budgets, and CRM implementations specifically have historically failed about half the time. Vendors engineer this lock-in deliberately — through tangled proprietary schemas and **data egress fees** that can run tens of thousands of dollars per petabyte just to retrieve your own records. The technique that makes a low-risk move possible is a **parallel cutover** powered by change-data-capture pipelines (open-source tools like Debezium and Apache Kafka). Think of Debezium as a wiretap on your legacy database log: every change streams in real time to the new system, creating a live, continuously updated copy. A proxy sits in front of users and writes to both systems at once, so you can validate the new one against real production traffic for weeks before handing over the keys — like forwarding your mail to two houses and checking every letter arrives before you move. It works, but it's masterful execution, not a toggle: API extraction limits, throttling, and synchronization drift from mismatched field rules all have to be validated across thousands of edge cases first.

## Where a platform like halfoff.ai fits

This is the niche platforms such as halfoff.ai are built to occupy: rebuilding the SaaS you already use on managed open-source infrastructure, handling the clean-room rebuild and the data migration, and running the result for you — with the pitch that you keep the code and data at the end. It's a coherent answer to everything above: the price inflation, the lock-in, the operational burden, and the legal boundaries.

The honest way to evaluate any provider in this space — halfoff.ai included — is to treat the headline figures (savings percentages, "zero downtime," "zero exit fees") as claims to be verified, not facts. Ask how the managed fee compares to compounding renewals over five years, demand to see how the CDC pipeline handles your platform's specific API limits and field dependencies, and get the clean-room indemnification in writing. A provider confident in its method should welcome those questions.

## The takeaway

SaaS repatriation has graduated from a niche IT preference into a financial and legal strategy. At its core, it converts software from a perpetually inflating, unpredictable operating expense back into an owned, capitalized asset — equity in your own infrastructure instead of rent you'll pay forever. Even if you never migrate a single system, understanding clean-room cloning and zero-downtime cutovers changes the power dynamic in your next renewal negotiation. You stop being a captive audience.

If your software bill climbs every year for features you didn't ask for, the most valuable first step isn't switching vendors — it's modeling your true five-year total cost of ownership and learning what a credible, well-indemnified escape route would actually require. The trap only works on those who don't realize the door is open.
