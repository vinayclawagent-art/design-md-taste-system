# VinClawLabs Mission Control DESIGN.md Sample

Source loop: [[../../Improvement-Loops/Design.md Taste System Loop|Design.md Taste System Loop]]

```yaml
brand:
  name: VinClawLabs Mission Control
  personality: operator-led, sharp, technical, premium, pragmatic
  audience: AI builders, operators, and local-business automation buyers

principles:
  - Dense information, never cluttered.
  - Dark command-center base with high-contrast action color.
  - Proof blocks before hype blocks.
  - Mobile-first cards; desktop unlocks dashboards and side-by-side comparisons.

typography:
  display: Inter Tight or Geist, 700-850 weight
  body: Inter or system-ui, 400-520 weight
  code: JetBrains Mono or ui-monospace
  rhythm: short paragraphs, strong section labels, scannable bullets

colors:
  background: "#070A0F"
  surface: "#101826"
  surface_2: "#0B1220"
  text: "#F8FAFC"
  muted: "#94A3B8"
  line: "#253044"
  primary: "#22D3EE"
  secondary: "#8B5CF6"
  success: "#34D399"
  warning: "#FBBF24"

components:
  hero:
    style: oversized direct promise, one proof metric row, one primary CTA
  cards:
    style: rounded 20-24px, subtle border, dark translucent surface, compact metadata pills
  dashboards:
    style: four-column desktop metrics, stacked mobile, clear status colors
  ctas:
    style: gradient cyan-to-green for primary, dark outlined secondary

motion:
  rule: subtle reveal and state changes only; no bouncing or playful gimmicks
  duration: 120-220ms

avoid:
  - pastel startup gradients with no contrast
  - generic AI sparkle icons everywhere
  - walls of abstract copy before proof
  - desktop-only layouts
```

## First application target
Apply this sample to one existing artifact prototype, then compare it against the current style for consistency and perceived trust.
