# The Hidden Cost of "Sorry, Can You Repeat That?"

Think about the last time you were on a call where the audio was a mess. Maybe there was background noise, or an accent you weren't used to processing, and you found yourself leaning into the screen, squinting, until you finally had to say it: "Sorry — can you repeat that?"

It feels like a tiny moment. A minor friction point in an otherwise normal day. But that single moment of hesitation, repeated across millions of conversations, turns out to be a measurable drain on people, performance, and budgets. It has a name — acoustic friction — and once you see the scale of it, the case for fixing it becomes hard to ignore.

This article unpacks what acoustic friction actually costs, why your brain finds bad audio so exhausting, and what to look for in the real-time voice technology now emerging to address it — including the hard questions every buyer should ask before deploying it.

## What acoustic friction really costs

"Can you repeat that?" isn't just awkward. It's expensive.

Industry analysis of the UK contact center market found that a single 15-second repetition — asking someone to say one sentence again — accounts for roughly 4.2% of an average call's total duration. That sounds trivial until you multiply it across the billions of inbound calls handled every year. By that estimate, acoustic friction costs the UK contact center industry alone in the region of £143 million (about $170 million) annually. That's money evaporating, one "sorry, what was that?" at a time.

For anyone running a contact center, a BPO, or a distributed support operation, that's not an abstraction. It's call duration, agent capacity, and customer patience leaking out of the system every single day.

## Why bad audio exhausts your brain

The financial cost is a symptom. The deeper problem is biological, and it explains why a day of difficult calls leaves people genuinely depleted.

Research from the University of Gävle in Sweden examined the cognitive drain of certain kinds of background noise — particularly the "halfalogue" effect: hearing only one side of a nearby conversation. Steady, predictable noise, like an air conditioner or constant traffic, is easy for the brain to filter out. But a half-heard conversation is unpredictable in both timing and content, and the brain can't leave that gap alone. It involuntarily burns energy trying to predict the missing half.

A useful way to picture it: it's like a glitching text-prediction engine on your phone. When the software hits a word it can't guess, the little wheel just spins and spins, the processor runs hot, and the battery drains — all to solve a puzzle it doesn't have the pieces for. Your brain does the same thing with unclear audio, quietly draining your cognitive battery on a conversation you may not even be part of.

This is why "Zoom fatigue" and contact center burnout aren't just complaints about long shifts. They're measurable responses to continuous cognitive depletion. The operational fallout is real: data cited from Iris Audio Technologies indicates that around 89% of contact center agents report background noise disrupting their calls daily, and that constant drain can lower a bystander's cognitive performance by up to 30%. Spend eight to ten hours a day fighting that, and it's no surprise the industry tracks agent turnover as high as roughly 58%. The chaos is, quite literally, driving people out of the job.

## The hardest friction point: accents and identity

Ambient noise is one thing. The most sensitive friction point is human: accents and language barriers.

When a customer calls in already frustrated and then hits a comprehension barrier — leading to transfers or callbacks that blow first-contact resolution — satisfaction scores can fall sharply. For years, the business world's answer was manual "accent neutralization": millions of offshore agents, heavily concentrated in regions like the Philippines and India, drilled to suppress their native inflection, adopt anglicized names, and memorize Western colloquialisms.

This is where the conversation gets genuinely contested, and it's worth presenting both sides honestly rather than picking one.

Critics — particularly applied linguists — argue that forcing people to alter their natural speech frames the voices of racialized speakers as deficient or unprofessional, and that using AI to morph a voice toward a dominant dialect simply automates a hierarchy of "acceptable" speech. They describe it as a kind of erasure.

Proponents frame the same technology as worker protection. Offshore agents frequently face hostility and bias the moment an accent is detected, and real-time accent harmonization can act as a buffer — while also sparing agents the exhausting work of suppressing their own identity through manual training. There's an economic argument too: market analysts at Frost & Sullivan suggest that removing the accent barrier lets organizations hire for talent and empathy rather than for a pre-existing Western accent, potentially expanding recruitment into more regions.

The honest takeaway isn't that one side is right. It's that any organization adopting this technology is walking an ethical tightrope, and should do so deliberately — with a clear stance on consent, transparency, and whether the goal is to *enhance* communication or *erase* difference.

## What actually makes real-time voice AI work

The reason this debate matters now is that the engineering has finally caught up to the ambition — and understanding how helps you evaluate vendors instead of taking marketing at face value.

The old approach, "cascaded" architecture, was a multi-step pipeline: convert speech to text, send the text to a model for translation, then synthesize new audio. Every step adds delay, and the moment you reduce a voice to plain text you throw away the emotion — the model reading "I need help" has no idea whether the speaker is calm or panicking. The result sounds sterile, and the lag makes natural turn-taking impossible.

How much lag is too much? The relevant telecom standard holds that one-way latency should stay below about 150 milliseconds for conversation to feel natural; past roughly 400 milliseconds, it collapses into awkward pauses and people talking over each other.

This is also where a healthy dose of skepticism pays off. You'll see platforms advertise "zero latency" — but given the physics of data crossing the globe, zero latency is a marketing myth. The real engineering target is *imperceptible* latency: fast enough that humans don't notice. The breakthrough enabling that is direct speech-to-speech translation, which skips the text step entirely and manipulates the audio signal itself, shifting pronunciation while preserving the speaker's pitch, rhythm, and emotion. Done well, a frantic voice stays frantic and a calm one stays calm — less a robotic text-reader, more a real-time interpreter.

## The questions every buyer must ask

If you're evaluating real-time voice AI, the capabilities are only half the diligence. The other half is risk. A few questions separate serious vendors from the rest:

- **What happens to voice data?** Mapping a voice precisely is, in effect, a blueprint for a deepfake. Under regulations like the EU's GDPR, a digitized voice map can be treated as biometric data, not ordinary personal information — which raises the stakes on storage. Ask whether the platform ever stores a playable audio file (the safer answer is no), and how voice templates are protected if a server is breached.
- **How is latency actually measured?** Push past "zero latency" claims and ask for real numbers against the sub-150-millisecond benchmark.
- **How is quality verified?** Subjective "does this sound clear?" panels aren't enough. Mature vendors use objective, algorithmic metrics — comparing processed audio against the original signal — to prove the system preserves the speaker's identity rather than just smoothing noise.
- **Where are the hard limits?** In high-stakes settings, boundaries matter. In healthcare, for example, real-time voice AI may be appropriate for administrative tasks like scheduling and billing inquiries — but it should not be used for clinical diagnosis or to replace a certified human medical interpreter when a clinician is treating a patient.

Even if you never sign a contract, these are the right questions to protect your people, your customers, and your compliance posture.

## Where Polished.CX fits

Most of what makes voice AI trustworthy comes down to a single principle: clarity without erasure. The aim isn't to flatten how people sound — it's to remove the friction that gets in the way of being understood, while keeping the speaker's natural voice, tone, and emotion intact.

That's the space Polished.CX is built for: a real-time voice layer designed to localize accents, reduce noise, and translate across languages while preserving the speaker's voice identity — positioned around the idea of *enhancing* communication rather than erasing who someone is. For teams wrestling with the costs and questions in this article, it's one option worth evaluating against exactly the criteria above: latency you can verify, privacy you can document, and an ethical stance you're comfortable standing behind.

## The takeaway

"Sorry, can you repeat that?" is a small phrase carrying a large hidden cost — in money, in cognitive load, and in the human toll on the people doing the talking. The technology to reduce that friction is real, and it's improving fast. But the organizations that adopt it well won't be the ones chasing impossible promises like "zero latency" or "perfect" voice. They'll be the ones who treat clarity as something you earn responsibly: fast enough to feel natural, private enough to trust, and respectful enough to enhance a voice without erasing it.

If your team loses time and energy to acoustic friction every day, it's worth understanding what modern voice AI can — and can't — do about it. That understanding is where any good evaluation starts.
