# TEN:TEN Watches — Brand Kit

**TEN:TEN** is an experimental watchmaking brand that rescues and restores orphaned mechanical movements, then builds entirely new watches around them. Each movement becomes the starting point for a unique design, preserving both the machine and its history while giving it new life.

This repository is the home of the brand. Everything that defines TEN:TEN — what it stands for, how it talks, how it looks, and how it makes things — lives here in one organised place. It is built so both people and AI tools can use it.

---

## New here? Read this first

A few words you'll see, in plain English:

- **This page (a "repository" or "repo")** — a tidy collection of files hosted on GitHub. Click any folder or file to open it.
- **`.md` files** — plain text files called Markdown. Click one and it shows up as formatted text, like a web page. You can read them right here in your browser.
- **A "skill"** — a ready-made page of instructions you give to an AI tool (like Claude) so it responds in TEN:TEN's voice and look. Think of it as a recipe: paste it in, add your request, get an on-brand result.
- **The media library** — all images and approved assets live in a Dropbox folder (link below), not in this repo, so this stays light and fast.

---

## What do you want to do?

| I want to… | Go here |
|---|---|
| Understand the brand (mission, voice, look) | Open `brand/` and start with `foundation.md` |
| Write something on-brand (copy, taglines, product descriptions) | Use the `brand-writer` skill — see How to use a skill below |
| Direct an on-brand image | Use the `image-art-director` skill |
| Check if something is on-brand | Use the `copy-reviewer` or `image-reviewer` skill |
| Get logos, photography, or other assets | Open the media library (Dropbox) below |

---

## How to use a skill (step by step)

No coding required. If you can copy, paste, and type, you can do this.

1. **Open the skill.** Go to `skills/`, open the category folder (`generation` or `governance`), then the skill you want (e.g. `generation/brand-writer`), and click its `SKILL.md` file. Select all the text and copy it.
2. **Open Claude** at claude.ai and paste the skill text in.
3. **Attach any brand files the skill asks for.** Near the top, each skill lists the files it needs (e.g. `voice.md`). Download those from the `brand/` folder and attach them to your chat.
4. **Tell it what you need** — e.g. "Write a product description for a movement from a 1952 Elgin pocket watch."
5. **Done.** Claude replies on-brand. Ask for tweaks as you would in any conversation.

> Skills point to the real brand files rather than duplicating them. There is only ever one source of truth — the `brand/` folder.

---

## The toolbox (skills)

**Generate**
- `brand-writer` — writes on-brand copy for any context: product descriptions, movement histories, taglines, social posts, press notes.
- `image-art-director` — writes the prompt you paste into an image generator (Midjourney, GPT Image, Fuser) for on-brand photography and campaign imagery.
- `voice-rewriter` — takes any text and rewrites it in TEN:TEN's voice.

**Govern**
- `copy-reviewer` — scores a piece of writing against the brand and flags what's off, with suggested fixes.
- `image-reviewer` — evaluates an image against the visual identity and flags what's on- or off-brand.

---

## What's in here

| Folder | What it holds |
|---|---|
| `brand/` | The brand itself — foundation, mission, audience, voice, and visual identity. Start here. |
| `brand/visual/` | Visual identity specifics — typography, color, photography, logo, layout. |
| `skills/` | AI helpers for generating and reviewing on-brand work. |
| `assets/` | Index pointing to the media library. No large files are stored here. |
| `examples/` | A worked example showing the skills used together. |
| `CLAUDE.md` | Instructions for AI sessions working in this repo. |

---

## Images and assets

All TEN:TEN visuals — logos, approved photography, hero assets, and reference imagery — live in the media library:

➡️ **[Open the media library](#)** *(Dropbox link — add when ready)*

---

## The idea behind all of this

The brand is written down once, in plain files, so everyone — and every AI tool — works from the same truth. Generate something, check it against the brand, ship it. No scattered documents, no guesswork, no "which version is right?"
