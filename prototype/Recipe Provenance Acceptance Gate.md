# Recipe Provenance Acceptance Gate

Source package: [[../../Generated-Packages/Design.md Taste System/README|Design.md Taste System]]
Loop: [[../../Improvement-Loops/Design.md Taste System Loop|Design.md Taste System Loop]]
Prepared: 2026-06-07
Status: acceptance gate ready for the next Design.md-generated prototype

## Purpose

Use this gate before accepting any future Design.md-generated screen. It turns the provenance-chip lesson from `mission-control-applied.html` into a repeatable review step instead of a one-off visual fix.

## Required visible provenance

Every accepted generated screen must show a visible recipe-provenance chip or footer that names:

1. The `DESIGN.md` recipe used.
2. The screen or artifact generated from it.
3. The checklist or skill draft used to verify it.
4. A short, human-readable reason the UI would not pass as a generic startup screen.

## Acceptance table

| Check | Evidence to attach | Pass / fail |
|---|---|---|
| Recipe chip is visible without opening dev tools | Screenshot or HTML snippet | _TBD during review_ |
| Chip names the exact recipe artifact | Link to `VinClawLabs Mission Control DESIGN.md Sample` or successor recipe | _TBD during review_ |
| Screen includes at least two recipe-specific nouns | List nouns and where they appear | _TBD during review_ |
| CTA names the next agent/product action | Copy CTA text | _TBD during review_ |
| Generic baseline delta is documented | Link to comparison note or one-paragraph delta | _TBD during review_ |
| Follow-up is actionable | One concrete change for next pass | _TBD during review_ |

## Copyable provenance-chip pattern

```html
<div class="recipe-chip" aria-label="Design recipe provenance">
  Recipe: VinClawLabs Mission Control DESIGN.md · Verified by Design.md Taste System checklist · Delta: artifact-factory nouns, repo proof, and agent-loop CTAs
</div>
```

## Copyable review note

```markdown
### Recipe provenance acceptance gate
- Screen reviewed: 
- DESIGN.md recipe: 
- Visible chip location: 
- Recipe-specific nouns: 
- Generic baseline delta: 
- Decision: accept / revise
- Follow-up for next pass: 
```

## Next action

Use this gate on the next Design.md-generated prototype before marking it accepted. This artifact prepares the review path; it does not claim a new screen has already been validated.
