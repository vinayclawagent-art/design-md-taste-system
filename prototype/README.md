# Design.md Taste System Prototype

Source package: [[../../Generated-Packages/Design.md Taste System/README|Design.md Taste System]]

Open `index.html` in a browser.

What it demonstrates:
- Intake for brand references and product personality.
- Generated outputs: DESIGN.md, landing page tokens, skill-pack notes.
- A productizable workflow for making agent-built products visually consistent.

Next iterations:
- Add the before/after check to the skill draft so future generated screens can be reviewed procedurally.
- Add export buttons.
- Host on here.now when ready for visual review.

## Design recipe artifacts

- [[VinClawLabs Mission Control DESIGN.md Sample]] — the concrete brand/taste recipe for VinClawLabs Mission Control.
- [[Mission Control Applied Screen Spec]] — applies the recipe to an Artifact Factory Command Center screen with proof metrics, status colors, and anti-pattern checks.
- `mission-control-applied.html` — the first concrete applied screen.
- `before-after-comparison.html` — a side-by-side taste verification artifact that contrasts a generic AI dashboard with the Design.md-applied Mission Control screen.
- [[Taste Verification Pass - Mission Control Applied Screen|Taste Verification Pass - Mission Control Applied Screen]] — pass/fail evidence for the applied screen, including concrete deltas against the generic baseline and one follow-up provenance-chip improvement.

## Taste verification checklist

Use the before/after comparison before accepting a generated UI:

1. Does the screen use VinClawLabs-specific nouns rather than generic SaaS labels?
2. Does the CTA name the next agent action?
3. Are proof metrics visible above generic activity counts?
4. Would the screen still make sense if copied into a random startup? If yes, the taste layer is too weak.

## Latest verification run

- 2026-06-03: `mission-control-applied.html` passed the taste verification checklist. The strongest deltas were VinClawLabs-specific artifact-factory nouns, proof/repo-sync metrics above generic activity counts, and CTAs that describe concrete agent actions. Follow-up: add a visible recipe-provenance chip to future generated HTML screens.
