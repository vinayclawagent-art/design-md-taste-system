# Design.md Taste System

GitHub-published X Artifact Factory package.

## Why this exists
Inspired by the linked X-Intel source note and maintained from `/home/vinclaw/Documents/Obsidian/x-intel`.

## What it contains
- `artifact-package/` — package note and product framing
- `prototype/` — clickable or inspectable prototype artifacts
- `infographic/` — workflow explanation when available
- `skill-draft/` — reusable-agent procedure draft when available
- `improvement-loop/` — recurring improvement tracker when available

## Latest improvement
- 2026-06-11: Added `prototype/Design.md Post-Trial Debrief Template.md` so the next real Design.md-generated screen review can turn packet/gate evidence into an accept / patch / iterate / reject decision and a concrete token/prototype/skill patch queue. Template-ready only; validation still depends on a real screen review.

## Quickstart
Open files directly. For HTML prototypes:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/prototype/` or open the HTML file. For the next review, fill `prototype/Design.md Screen Review Trial Packet.md`, `prototype/Recipe Provenance Acceptance Gate.md`, and `prototype/Design.md Post-Trial Debrief Template.md`.

## Source
This repo is synced from Vinay's X-Intel Artifact Factory vault.
