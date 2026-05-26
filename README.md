# Hello iPhone

This repo contains a reusable Codex skill derived from the 2007 iPhone launch. The point is not to rebuild that keynote for its own sake. The point is to apply its rhetorical product-pitch architecture to new products and new formats: decks, websites, launch posts, sales materials, demo scripts, founder stories, investor narratives, and other go-to-market artifacts.

The included Slidev deck is the reference case. It breaks down how the iPhone launch changes audience belief through category framing, status-quo contrast, mechanism reveal, demo proof, repetition, value anchoring, and a compressed close.

## Skill

`SKILL.md` is an agent-facing playbook for adapting the iPhone launch structure to other products.

Use it when you want Codex to create persuasive materials that:

- name the old-world compromise
- show why the category is structurally stuck
- reveal the product mechanism that breaks the tradeoff
- prove the claim through concrete actions and evidence
- alternate novelty with familiar adoption bridges
- close with a line the artifact has already earned

The skill is structural, not cosmetic. It should not produce generic Apple homage, black-stage mimicry, or Steve Jobs pastiche unless explicitly requested.

## Reference Deck

The local deck documents the source pattern:

- `slides.md` - Slidev analysis deck
- `style.css` - visual system for the analysis deck
- `assets/source-slides/` - rendered pages from the companion iPhone launch slide PDF
- `source/` - extracted text from the supplied transcript and rhetorical-techniques source material
- `SKILL.md` - reusable adapter for applying the pitch framework to other products

## Run The Reference Deck

```bash
npm install
npm run dev
```

Then open `http://localhost:3030/`.

## Build

```bash
npm run build
```

The generated site is written to `dist/`, which is intentionally ignored.

## How To Use This Repo

Point Codex at this folder when you want to reuse the launch framework. Provide the target product, audience, desired medium, proof points, and desired action. Codex should use `SKILL.md` to turn the iPhone launch anatomy into a new artifact for that product.

Example request:

> Use this skill to create a launch deck for a compliance automation product aimed at regional banks. Make it structural, not Apple-cosplay.

The output should fit the new product's brand, evidence, and audience while preserving the underlying belief-change sequence.
