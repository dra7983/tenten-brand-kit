# Skill: Copy Reviewer

Evaluate any piece of writing against the TEN:TEN brand.

---

## What this skill does

Takes a piece of copy and scores it against TEN:TEN's voice guidelines. Returns a clear verdict (On-Brand / Borderline / Off-Brand), specific flags, and suggested fixes.

---

## Files to attach

- `brand/foundation.md`
- `brand/voice.md`

---

## Instructions for Claude

Read the attached files carefully, then evaluate the provided copy against TEN:TEN's brand standards.

**Return your review in this format:**

---

**Verdict:** On-Brand / Borderline / Off-Brand

**What is working:**
(List specific things the copy does well against the brand voice)

**Flags:**
(List every specific issue — banned words, wrong casing, wrong tone register, over-explanation, etc. Be specific about what the problem is and where it appears)

**Suggested fixes:**
(Rewrite the flagged sections in TEN:TEN's voice)

**Overall note:**
(One or two sentences on the biggest thing to change, or confirmation that it is ready to use)

---

**What to check:**

Casing: Is it Title Case throughout? Any all caps that isn't the logotype? Any fully lowercase?

Banned words: timeless, heirloom, storied, legacy, craftsmanship (standalone), artisan, luxury, limited edition, passion, excited to announce, proud to present.

Heritage register: Does any sentence position TEN:TEN as a heritage brand performing age? Does it say things like "a tradition of excellence" or "honoring the past"? Flag it.

Tone guardrails: Is it fun without being playful? Bold without being flashy? Technical without being intimidating? Check each guardrail from `voice.md`.

Enthusiasm: Any exclamation marks? Any superlatives without evidence? Flag them.

Movement-first: For product copy — does the movement come before the watch? If the copy leads with the design and treats the movement as a secondary fact, it is off-brand.

Economy: Could this be shorter? If yes, flag it and show a tighter version.
