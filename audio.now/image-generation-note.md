# Image Generation Note

## Blocker
ChatGPT output did not match the requested LinkedIn image direction.

## What happened
- A dedicated ChatGPT chat was used (auto-titled "LinkedIn Feed Image Request"), separate from the blog-generation chat.
- The approved instruction wrapper + the contents of `linkedin-image-prompt.md` were pasted and submitted.
- ChatGPT generated one image successfully and offered a download option (no refusal, no download failure).
- However, the generated image did not follow the prompt. ChatGPT produced a warm-toned product shot it titled "Sleek laptop levitating in minimalist studio": a black laptop floating above a stone pedestal in a bright beige studio, with an orange/grey abstract wallpaper shown on the laptop screen and translucent orange geometric panels.

## Why it is a mismatch
The prompt explicitly required the opposite of what was produced:
- Requested: abstract and metaphorical, with NO devices in focus and NO UI/app screens. Result: a laptop device is the hero subject and a UI/wallpaper screen is prominently shown.
- Requested: cool, low-saturation palette — deep navy / charcoal background with soft teal and muted electric-blue accents. Result: bright warm beige background with orange accents.
- Requested: concentric audio ripples and a soundwave meeting a faint boundary/grid. Result: none of these elements are present.
- Requested: wide ~1.91:1 LinkedIn feed format. Result: closer to a landscape product render, not the specified editorial concept.

## Action taken
- Did not fail the test.
- Kept `linkedin-image-brief.md` and `linkedin-image-prompt.md`.
- Did not overwrite the existing `linkedin-image.png` in this folder with the off-brief ChatGPT result.
- Stopped after saving this note, per the add-on instructions.

## Context (other tools)
- Gemini ("Pro") generated an on-brief image in a separate run (navy background, teal concentric ripples and soundwave, faint boundary grid, off-white negative space, no text/logos/devices). That image was downloaded by Gemini to the computer's Downloads folder; it could not be auto-moved into this folder because the sandbox cannot access the Downloads location.
- The current `linkedin-image.png` in this folder is a clean, on-brief asset rendered locally to the same direction (1200x627, navy + teal ripples).

## Suggested next step (optional)
If a ChatGPT-generated asset is still wanted, re-run with a sharper constraint, e.g. lead with: "Abstract only. No laptop, no phone, no device, no screen, no UI. Cool navy background, teal/blue audio ripples." Otherwise use the Gemini result or the local `linkedin-image.png`.
