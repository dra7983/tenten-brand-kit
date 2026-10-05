# CLAUDE.md — TEN:TEN Brand Kit

Instructions for any AI tool working in this repository.

---

## What this repo is

This is the brand kit for TEN:TEN Watches — an experimental watchmaking brand that rescues and restores orphaned mechanical movements and builds entirely new watches around them. Everything in this repo defines the brand: what it stands for, how it speaks, how it looks, and how to make things with it.

---

## How to use this repo

**Always start with the brand folder.**
`brand/foundation.md` is the source of truth for the brand's mission, audience, and principles. `brand/voice.md` governs all writing. `brand/visual/` contains the full visual identity.

**Skills are instructions, not templates.**
The files in `skills/` are instructions for how to do a specific task on-brand. Read the skill, attach the brand files it requests, then complete the task.

**One source of truth.**
Do not duplicate brand information across files. If you are updating the brand, update the canonical file in `brand/`. Skills point to those files — they do not contain copies of the rules.

---

## Critical brand rules (read before doing anything)

**Voice:**
- Title Case throughout. Never all caps (the logotype TEN:TEN is a fixed mark and the only exception). Never fully lowercase.
- Active voice. Present tense where possible.
- No exclamation marks. No superlatives without evidence.
- Do not position TEN:TEN as a heritage brand. Banned words: timeless, heirloom, storied, legacy, craftsmanship (standalone), artisan, luxury, limited edition, passion.

**Visual:**
- The brand is black and white. Color comes from photography and the watches — never from brand elements.
- The accent color (#BE3F00) is for interactive UI states only. Never in photography, print, or product contexts.
- The logotype (TEN:TEN) is a fixed mark. Do not recreate it. Do not use it in the accent color. Do not apply effects to it.

**Product:**
- The movement comes before the watch. Always. In copy, in photography direction, in everything.
- TEN:TEN does not manufacture scarcity. It inherits it. Do not describe products as limited edition.

---

## File map

```
brand/
  foundation.md        — Mission, audience, principles
  voice.md             — Tone, writing rules, vocabulary
  visual/
    overview.md        — Visual identity principles
    typography.md      — Typefaces, weights, casing, hierarchy
    color.md           — Palette, accent usage, color system
    photography.md     — Shoot categories, style, campaign mode
    logo.md            — Logotype configurations, usage rules

skills/
  generation/
    brand-writer/      — Write on-brand copy
    image-art-director/ — Write image generation prompts
    voice-rewriter/    — Rewrite any text in TEN:TEN's voice
  governance/
    copy-reviewer/     — Evaluate copy against brand standards
    image-reviewer/    — Evaluate images against visual identity

assets/
  README.md            — Index pointing to the media library (Dropbox)

examples/
  product-launch.md    — Worked example: launching a new watch

README.md              — Front door of the repo
CLAUDE.md              — This file
```
