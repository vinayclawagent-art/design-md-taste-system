---
type: skill-draft
status: draft
source_package: "[[../../Generated-Packages/Design.md Taste System/README|Design.md Taste System]]"
tags: [skill-draft, design-md, ai-product]
---

# design-md-taste-system skill draft

Do not promote yet: the installed `design-md` skill already handles the DESIGN.md spec. This draft is a companion workflow for turning references into a product-specific taste system and asset skill pack.

```markdown
---
name: design-md-taste-system
description: Create a product-specific DESIGN.md taste recipe plus reusable asset-generation skill pack from brand references.
---

# Design.md Taste System

## Triggers
Use when building a product, landing page, pitch deck, app screen, or promo asset that needs consistent brand taste across multiple AI-generated outputs.

## Inputs
- Product name and target user
- 3-5 reference brands or screenshots
- Desired personality: premium, playful, technical, local-business, etc.
- Required artifact types: landing, app, deck, social, motion

## Steps
1. Extract visual rules from references: typography, color, spacing, layout density, component motifs, motion restraint.
2. Write `DESIGN.md` with concrete tokens and examples, not vague adjectives.
3. Create 2-4 narrow generation prompts/skills that must reference the same `DESIGN.md`.
4. Generate one sample artifact per skill.
5. Compare outputs for consistency and patch the design recipe before creating more assets.

## Before/after taste verification checklist
Use this checklist before treating a generated artifact as proof that the taste system works:

1. **Recipe linkage:** the artifact names the exact `DESIGN.md` recipe, version/date, and product surface it used.
2. **Token adherence:** typography, color, radius, shadow, spacing, and component density match the recipe instead of drifting to model defaults.
3. **Generic baseline:** keep or create one intentionally generic AI output for the same screen so the taste lift is visible.
4. **Specific deltas:** record at least five before → after changes, such as “blue SaaS gradient → ink/ember command palette” or “equal cards → priority ladder.”
5. **Cross-surface consistency:** verify the same rules work on at least two asset types before expanding the skill pack.
6. **Patch loop:** if two or more checks fail, patch `DESIGN.md` first; do not compensate with one-off prompt adjectives.

## Pitfalls
- Do not copy a reference brand; translate design language into original constraints.
- Avoid generic words like beautiful/premium unless tied to observable rules.
- One polished page is not proof; verify consistency across at least two asset types.

## Verification
- `DESIGN.md` has typography, color, spacing, components, voice, and don't-do rules.
- Each generated artifact explicitly links back to the design recipe.
- Before/after comparison shows reduced visual drift.
- The verification checklist has a pass/fail note and at least five concrete before → after deltas.
```
