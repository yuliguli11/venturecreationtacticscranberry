# Ruby Reserve — Brand & UI System (v0.1)

**CPG Cranberry (Ruby Reserve)** turns organic cranberries into an elevated, sweet-tart luxury snack for mindful everyday indulgence, entertaining and thoughtful gifting.

Prototype: [`design/index.html`](index.html). Open it in a browser. It's a single static file that needs no build step.

> No custom logo, font or photography assets have been supplied yet. The wordmark, pouch/tin illustrations and color-blocked pairing cards are **placeholder components**. Replace them when real assets exist.

## Who it's for
Maya Chen, 34, an urban tech/marketing manager ($110k–$140k). She wants a craveable, sweet-tart snack that sits between utilitarian fruit snacks and luxury confections: something for the 3–4 PM desk break, the cheese board and the hostess gift. She browses on mobile in transit and on desktop at work.

## Color tokens
| Token | Light | Dark | Role |
|---|---|---|---|
| `--ground` | `#F6EFE4` warm ivory | `#170A0D` | Page background (never stark white) |
| `--paper` | `#EEE3D2` soft cream | `#22110F` | Alternating editorial bands |
| `--ink` | `#2B1116` | `#F2E7D8` | Text |
| `--muted` | `#6B5550` | `#BCA79D` | Secondary text |
| `--ruby-fill` | `#7A1528` deep matte ruby | `#8E1B31` | Primary CTA, packaging, color blocks |
| `--ruby-deep` | `#4A0C18` | `#3A0912` | Hover, footer band, counter line |
| `--copper` | `#9C5A31` | `#D59A6A` | Eyebrows, hairline accents, focus ring |
| `--copper-soft` | `#D9A77C` | `#8A5A36` | Gift / tin color block |
| `--pine` | `#2E4A3B` | `#2A4536` | Botanical accent, "what we leave out" |

Avoid neon red, candy magenta, clinical white and digital gradients.

## Typography
- **Display: Bodoni Moda** (high-contrast Didone, optical sizes). Headlines at weight 400–500, with italic for emphasis and the wordmark. It reads as literary and atelier-made.
- **Body/UI: Source Sans 3** (humanist sans). 17px body, never below 16px. Uppercase labels at 14px with +0.08–0.14em tracking.
- Scale: 14 / 17 / 20 / 26 / 30–42 / 42–76px.

## Layout & interaction
- Editorial, generous whitespace, 1200px max, 16–48px fluid gutter.
- All tap targets are at least **48px** (buttons, chips, rail arrows, close).
- One-click add: pick a flavor once (shared between the Flavor Profiles and Shop sections), then add a Pouch, Tin or Trio with a single click.
- Interactive flavor profile cards show the sweet↔tart and tender↔crisp scales, tasting notes, pairings and the **full ingredient list**.
- "Entertaining & Gifting" is a rail of tall, full-bleed cards with scroll-snap, arrow buttons and swipe. The visual language is borrowed from Instagram/TikTok, but the pace is calm.
- Light and dark themes; respects `prefers-reduced-motion`.

## Voice
- Use culinary verbs such as "Reserve Your Box", "Explore Pairings" and "Savor". Never "BUY NOW".
- Frame copy around occasions: "Perfect for 4 PM desk breaks or tonight's cheese board."
- Keep it calm when helping: empty box → "Let's get your pantry stocked." Form errors say what's wrong and how to fix it.
- Be transparent: list exact ingredients and sourcing, and make no health claims.

## Don'ts
- No SUPERFOOD/antioxidant/UTI claim bursts.
- No glassmorphism, 3D candy blobs or neon overlays.
- No discount banners or countdown timers.
- No farmhouse-jam styling or cartoon fruit.
- Don't look like mass-market Craisins (glossy bags, primary red, mascots).

## Proxy cues
Graza (warm, modern treatment of a commodity ingredient), Brightland and Fishwife (editorial color-blocking, packaging that doubles as counter decor). The Counter Tin and the matte pouch are designed to sit out on the counter.
