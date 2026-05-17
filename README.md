# doggy-growth-plan-landing

Online presentation site for **Doggy Growth Plan / GG Bond**.

Live site:
- https://kndhjk.github.io/doggy-growth-plan-landing/

Source repo:
- https://github.com/kndhjk/doggy-growth-plan-landing

Related project repo:
- https://github.com/UOA-CS732-S1-2026/group-project-gg-bond

## What this is

This repo hosts a **bilingual seminar slide deck** for the CS732 group project **Doggy Growth Plan**.

It is no longer a simple landing page. It has been rebuilt into a multi-page online presentation with:
- Chinese / English switching
- slide-style navigation
- grouped speaker sections
- visual mockups
- lightweight motion effects
- QR entry to the live demo

## Current presentation structure

The deck is organized around the GG Bond team contribution split.

Current flow:
- Opening
- Project structure / overview
- Huanhuan Li
- Xingyan Zhou
- Ming Zhao
- Xiang Zhang
- Kejun Xu
- Jiayi Lyu
- GitHub / collaboration
- Closing / Q&A

At the time of writing, the deck contains **16 slides** in total.

## Highlights in the current version

- **Six-speaker layout**: each member has dedicated slides instead of being compressed into one overview page
- **Bilingual presentation**: Chinese and English content switch in-place
- **Mobile-friendly controls**: navigation works on phones without swipe-based accidental page changes
- **Visual support**: custom SVG diagrams plus product-style mockups for pet state, AI, community, matchmaking, and GitHub workflow
- **Speaker emphasis**: Ming Zhao's section is intentionally given stronger stage presence to reflect the integrator / system-linking role in the presentation

## Files

- `index.html` — main presentation file
- `assets/slides/*.svg` — custom visual diagrams used in the deck

## Design / implementation notes

This presentation is intentionally built as a **single-file static deck** plus lightweight assets so it can be:
- easy to deploy to GitHub Pages
- easy to edit quickly before a seminar
- easy to open on desktop or mobile
- independent from the main product runtime

The page currently includes:
- fixed top navigation
- slide jump dropdown
- bilingual text swapping through `data-cn` / `data-en`
- bottom pager controls
- lightweight CSS motion (`float`, `glow`, `shimmer`, highlight states)

## Related live demo

The presentation links to the test deployment of Doggy Growth Plan here:
- http://4.155.227.179/

## Editing notes

If you want to continue updating this deck, the most common edits are:
- refine per-speaker wording directly in `index.html`
- add or replace visuals under `assets/slides/`
- tune navigation labels in the `labels` array inside the script block
- adjust emphasis / pacing by changing slide grouping and top-nav targets

## Deployment

This repo is intended for GitHub Pages.

After pushing to the default branch, the site is published at:
- https://kndhjk.github.io/doggy-growth-plan-landing/

## Status

This repo is actively used as the seminar presentation surface for the GG Bond / Doggy Growth Plan project.
