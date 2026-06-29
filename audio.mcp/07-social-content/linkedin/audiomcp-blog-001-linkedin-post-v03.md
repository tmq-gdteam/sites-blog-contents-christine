If you're evaluating or building voice AI, most of the marketing won't help you. The mechanics will. A buyer's checklist drawn from how real-time voice actually works:

1. Treat sub-800ms as pass/fail. Measure latency at the conversational turn level — finish-of-speech to start-of-response — not raw model inference. ~800ms is where humans start perceiving a call as broken.

2. Pick the right transport. WebRTC is the faster path for in-app voice; SIP reaches real phone numbers but adds delay from legacy switches. Choose for your use case, and budget for SIP's cost if you need it.

3. Be skeptical of silence-based turn-taking. If interruption handling is just a "wait for silence" timeout, expect cut-offs or lag. Ask about semantic endpointing (reading intent in real time) and how barge-in truncates context.

4. Ask for the numbers. The strongest signal of a serious platform is transparent telemetry — median and tail (P50/P95) end-to-end latency and the underlying stack. "Zero latency" claims and black boxes are red flags.

5. Design security and consent from day one. An autonomous agent with a phone is a real-world actor — and independent research in early 2025 found only a small fraction of MCP servers used modern OAuth.

A new integration standard is convenient, but it doesn't make a slow pipeline fast. Judge any platform on whether it can show you the numbers, not just promise them.

Which of these is hardest for your team today?
