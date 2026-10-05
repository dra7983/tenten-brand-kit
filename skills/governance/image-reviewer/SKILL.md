# Skill: Image Reviewer

Evaluate any image against the TEN:TEN visual identity.

---

## What this skill does

Takes an image (attached to the chat) and evaluates it against TEN:TEN's visual identity guidelines. Returns a verdict, specific flags, and actionable fixes.

---

## Files to attach

- `brand/visual/overview.md`
- `brand/visual/color.md`
- `brand/visual/photography.md`
- The image to be reviewed

---

## Instructions for Claude

Read the attached visual identity files carefully, then evaluate the attached image.

**Return your review in this format:**

---

**Verdict:** On-Brand / Borderline / Off-Brand

**Category:** (Which photography category does this image belong to — workshop, storefront, lifestyle, product, or campaign?)

**What is working:**
(List specific visual elements that align with the brand)

**Flags:**
(List every issue with specifics — wrong color treatment, staging that feels artificial, brand colors appearing where they shouldn't, watch hands not at 10:10, etc.)

**Suggested fixes:**
(For each flag, a specific, actionable correction)

**Overall note:**
(One or two sentences on the most important thing to address, or confirmation that the image is approved)

---

**What to check:**

Color treatment: Is the image following the correct color rules for its category? Full color for workshop/lifestyle/product, selective color only for campaign imagery?

Campaign mode: If this is campaign photography, is the selective color applied surgically to the watch only? Does anything else in the frame carry color?

Product photography: Are the hands at 10:10? Is the ground white or black? Are there any styling elements that shouldn't be there?

Workshop photography: Does the lighting feel honest or artificial? If hands appear, do they look experienced? Are they wearing amber latex finger cots if the context requires it?

The watch as subject: Is the watch the most visually prominent colored element in the frame? If not, flag it.

Brand colors: Is the accent color (#BE3F00) appearing anywhere in the image? It should not. It is a UI-only color.

Staging: Does anything look artificially arranged to look unstaged? Flag it.
