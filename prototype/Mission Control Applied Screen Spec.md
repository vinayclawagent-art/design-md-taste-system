# Mission Control Applied Screen Spec

Source loop: [[../../Improvement-Loops/Design.md Taste System Loop|Design.md Taste System Loop]]
Design recipe: [[VinClawLabs Mission Control DESIGN.md Sample]]

This turns the sample `DESIGN.md` into a concrete screen direction for the current prototype so the loop is no longer only a generator concept.

## Screen: Artifact Factory Command Center

### Promise
Give Vinay one dense, trustworthy operator screen for deciding which X-derived ideas deserve prototype, infographic, skill, or GitHub-repo treatment next.

### Layout

1. **Hero command row**
   - Title: `Artifact Factory Command Center`
   - Subtitle: `Score X intel, spawn artifacts, and prove each improvement with commits.`
   - Primary action: `Open next active loop`
   - Secondary action: `Review GitHub-visible repos`

2. **Proof metrics**
   - `2 active loops improved this run`
   - `3 isolated repos created`
   - `100% artifact packages Git-tracked`
   - `0 recursive cron jobs spawned`

3. **Loop cards**
   - Each card shows source note, cadence, last improved date, next focus, and the next concrete artifact change.
   - Status colors follow the sample: cyan for action, green for shipped, amber for needs proof.

4. **Recipe trace panel**
   - Shows which `DESIGN.md` tokens were applied: background, surface, typography, proof-before-hype rule, and anti-patterns avoided.

## Applied taste tokens

| Token | Applied choice |
|---|---|
| Background | `#070A0F` command-center base with subtle cyan/violet glow |
| Surface | `#101826` / `#0B1220` cards with crisp `#253044` borders |
| Primary action | Cyan-to-green gradient, not generic purple-only startup CTA |
| Copy rhythm | Short proof-first lines; no abstract hype paragraph before metrics |
| Density | Four-column desktop metrics; stacked mobile cards |
| Avoided | Random AI sparkle icons, low-contrast grey text, desktop-only dashboard |

## Prototype update requirement

The current `index.html` should expose a proof metric strip and a recipe trace panel so reviewers can see that the DESIGN.md sample was actually applied, not merely stored as a note.

## Verification prompt

Ask after each generated screen:

> Can a viewer infer the product's operating promise, current proof, next action, and brand rules in under 20 seconds on mobile?

If not, tighten density and proof hierarchy before adding visual decoration.
