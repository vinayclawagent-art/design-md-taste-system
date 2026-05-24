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

## Pitfalls
- Do not copy a reference brand; translate design language into original constraints.
- Avoid generic words like beautiful/premium unless tied to observable rules.
- One polished page is not proof; verify consistency across at least two asset types.

## Verification
- `DESIGN.md` has typography, color, spacing, components, voice, and don't-do rules.
- Each generated artifact explicitly links back to the design recipe.
- Before/after comparison shows reduced visual drift.
```
