# FLOW-STATUS — read-only check 2026-10-18 ~02:00

## What I could check (subagent has no live browser)
- Fetched https://flow.google as text: renders only the landing page with a **"Sign in"** link. No balance, no project list, no generation — all behind Google sign-in.
- Checked /opt/hatch/bin: **no Flow/Gemini/Veo CLI exists**. ~/workspace/gemini-setup/ is only a checklist; ~/workspace/argon-test/ holds old test outputs.
- "Argon" is the owner's name for the image/video model inside his Gemini/Flow — there is no separate Argon service to probe.

## Verdict: COULD NOT VERIFY
I cannot confirm whether Flow is active or how many credits exist. Anything beyond the landing page needs the **parent's signed-in live-browser session** (the one already signed in as hamed hoseyni on gemini.google.com).

## What the parent must do in the live browser (no burn)
1. Open flow.google signed in → read the credit balance (top-right / billing).
2. Confirm Nano Banana (image) and Veo/Argon (video) are selectable.
3. Report back: balance + which models are available.

## Generation plan — READY TO RUN once confirmed active (do NOT run until balance is known)
Per the owner's 01:10 note: prompts engineered via Gemini/Argon itself, then:
1. **Garments (Nano Banana, image):** 35 items, ONE locked style prompt — "hanging on a black hanger, studio product shot, warm cream background, soft directional light" (the Mocha Relic rack look). Categories: 10 t-shirts, 10 shirts, 5 chinos, 5 jeans, 5 shoes. These REPLACE the stock set below for full visual uniformity.
2. **Model (Nano Banana, image):** photorealistic young male AI character, full-body, front-facing, neutral relaxed pose, warm dark-burgundy studio bg. Character-sheet discipline: front/side/back refs FIRST, then final. Replaces model-base.jpg. (Owner: realistic human/AI character — no plastic dummy, nothing cartoony.)
3. **71-frame rack rotation (Argon, video):** proof-of-concept on 2–3 garments ONLY. Do not burn all 35 until the PoC passes the owner's eye.

## Fallback actually delivered (this folder)
Since verification was impossible from here, I completed the **stock fallback (2b)**: 35 Pexels garments (free-commercial, no watermark, no attribution — see MANIFEST.md), v1's model-base.jpg reused, real Iranian market prices (see PRICES.md). The builder is NOT blocked: build v2 on this set now; swap in Nano Banana assets later if Flow proves active — same filenames/categories make the swap clean.
