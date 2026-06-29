There's a number that quietly governs every voice AI product: about 800 milliseconds.

That's the conversational latency budget — and it's written into human biology, not a config file. If the gap between you finishing a sentence and the AI replying stretches past ~800ms, your brain flags the conversation as broken. You assume it didn't hear you. You start talking again. Cue the awkward talking-over-each-other dance we all recognize from automated phone lines.

Here's the paradox: the same AI that writes flawless code in a chat box sounds clumsy on a call. The problem isn't intelligence or compute. It's the physics of conversation.

Most naive systems lose the budget inside a sequential pipeline — route the audio, transcribe it, run the model, synthesize speech, each step waiting for the last. Chain them and you can clear 2,000ms on every single turn. You've blown the budget twice over before doing anything clever.

The teams that win stop waiting. They stream partial words straight through the pipeline so everything overlaps instead of stacking. Sub-800ms isn't a premium feature anymore — it's the baseline a product needs just to survive contact with real users.

The lesson generalizes: when you move AI from text to real-time voice, you're not solving a smarter-code problem. You're fighting a clock.

If you're building or buying voice AI, what's the first number you'd measure?
