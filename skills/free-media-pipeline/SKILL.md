---
name: free-media-pipeline
description: Find and use genuinely available free or open-source tools for a YouTube video's image, video, voice, music, and editing workflow. Use when the creator asks to generate or assemble media under a zero-cost constraint, or when an existing provider quota is exhausted.
---

# Free Media Pipeline

Coordinate media production without assuming that an agent has provider credits, account access, or the ability to operate an external website.

## Non-negotiable budget policy

- Default spend ceiling is **0** in the creator's currency. Never buy credits, start a trial that requires payment details, subscribe, upgrade, or call a billable API without explicit approval for that exact charge.
- A public "free" claim is not proof that this user's account currently has usable credits. Verify the current provider pricing/quota documentation and the user's visible account balance or tool response before generation.
- Distinguish free daily credits, one-time trial credits, promotional credits, local compute, and paid credits. Record the date checked, region/account caveat, model, duration/resolution, and estimated credit cost.
- If the available balance is missing, insufficient, or unclear, do not press Generate. Offer a no-cost alternative or ask the user to check the displayed balance.
- Never claim that an external website was opened, an asset uploaded, or a video generated unless a connected tool returned confirmation.

## Workflow

1. **Define the deliverable.** Record aspect ratio, duration, resolution, visual style, source assets, audio needs, and required output format. Reuse the approved SYMBIOTIC character reference when present; do not regenerate approved artwork unnecessarily.
2. **Inventory connected capabilities.** Inspect tools actually exposed in the current runtime and the creator's connected apps. Separate:
   - callable generation/editing tools available now;
   - connected apps that can only edit or publish;
   - websites that the creator must operate manually;
   - local open-source tools that require a suitable machine.
   Do not treat an installed skill, GitHub repository, or website link as an executable integration.
3. **Research providers.** Use current official pricing, quota, model, region, and terms pages. Prefer provider-native free tiers and local/open-source tools. Community posts may suggest candidates but cannot establish a quota. Never promise credits based on stale third-party lists.
4. **Rank candidates.** Score quality for the requested style, free availability for this account/region, watermark/export limits, input-image support, duration/resolution, commercial-use terms, privacy, and setup effort. Exclude candidates that require payment for the requested output.
5. **Prepare before spending credits.** Draft the prompt, shot plan, and settings first. Prefer a single short proof-of-concept. Estimate the credit cost and compare it with the confirmed balance. Ask before generation if it consumes scarce promotional credits or if the user has not authorized that specific generation.
6. **Execute only through a real capability.** Call an available connected generation tool when its schema supports the task. If no such tool exists, provide the exact site link and concise steps for the user; do not claim to control their browser or account. Do not ask for passwords, one-time codes, or API secrets in chat.
7. **Verify the output.** Confirm the generated asset exists, inspect it when possible, and report actual duration, resolution, watermark, audio, and any defects. If generation fails, report the provider's returned reason and move to the next verified free candidate.
8. **Edit and assemble.** Use an actually connected editor (for example, Descript when its project tools are available) or a local open-source workflow such as HyperFrames/FFmpeg when runtime and dependencies permit. A production skill alone does not provide a rendering engine.
9. **Deliver and log.** Save assets and a compact provider log with date checked, provider/model, quota evidence, credit cost, output path, and remaining known limits. Publishing remains a separate approval step.

## Fallback order

1. Connected provider tool with a confirmed free allowance.
2. Provider's own free tier, only after the user confirms the visible balance and generation cost.
3. Local open-source generation/rendering if hardware, model license, and dependencies are suitable.
4. A production-ready prompt/storyboard and a clear blocker report if no free execution path exists.

Do not rotate through websites blindly. A provider is eligible only when its actual quota and the requested operation are verified.

## SYMBIOTIC initial test

For the approved cinematic AI-host image, prepare one 16:9 image-to-video test, 6–8 seconds if supported. Preserve the character design; subtle head movement, restrained red energy pulses, atmospheric smoke, and a slow camera push-in. No text, logos, cartoon styling, or unapproved redesign. Generate only after a free balance sufficient for the exact model and duration is confirmed.

## Reporting format

Report: **candidate → evidence of free access → exact cost → execution capability → result/blocker → next best free option**. Clearly label unverified claims.