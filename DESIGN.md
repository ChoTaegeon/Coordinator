---
name: Editorial Atelier
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4d4540'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#7e7570'
  outline-variant: '#d0c4be'
  surface-tint: '#625d5b'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1e1b19'
  on-primary-container: '#888380'
  inverse-primary: '#ccc5c2'
  secondary: '#755937'
  on-secondary: '#ffffff'
  secondary-container: '#fdd6ab'
  on-secondary-container: '#785c39'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#221a0f'
  on-tertiary-container: '#8e8272'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9e1dd'
  primary-fixed-dim: '#ccc5c2'
  on-primary-fixed: '#1e1b19'
  on-primary-fixed-variant: '#4a4643'
  secondary-fixed: '#ffddb7'
  secondary-fixed-dim: '#e5c096'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#5b4222'
  tertiary-fixed: '#efe0ce'
  tertiary-fixed-dim: '#d2c4b3'
  on-tertiary-fixed: '#221a0f'
  on-tertiary-fixed-variant: '#4f4538'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system embodies the intimacy of an haute couture salon merged with the precision of a modern digital concierge. It addresses discerning, style-conscious individuals who value effortless elegance, curatorial restraint, and intelligent personal styling. The emotional landscape is calm, exclusive, and refined—evoking the tactile luxury of heavy matte cardstock, bespoke tailoring appointments, and gallery lookbooks.

The design movement synthesizes **Editorial Minimalism** with **Warm Tactility**:
- **Generous negative space:** Interfaces breathe with intentional asymmetry and spacious margins reminiscent of high-fashion print magazines.
- **Warm materiality:** Surfaces lean away from cold, stark tech whites into creamy, organic linen tones.
- **Typographic hierarchy as texture:** Elegant, high-contrast serif headlines establish authority, while razor-sharp geometric sans-serif body copy delivers frictionless utility.
- **Quiet confidence:** Decorative ornamentation is kept minimal; depth and focus are communicated through proportion, aspect ratio, micro-interactions, and warm ambient light.

## Colors

The palette is anchored in organic warmth, replacing digital starkness with tactile, fabric-inspired hues:

- **Primary (`#1C1917` — Deep Espresso Charcoal):** The anchor for high-fashion typography, structural silhouettes, and primary interactive states. Offers deep contrast without the clinical severity of pure `#000000`.
- **Secondary (`#9A7B56` — Burnished Bronze):** Reserved for delicate accents, selected active states, curation badges, and signature focal points. It functions as jewelry on neutral garments.
- **Tertiary (`#D8CAB8` — Oat Beige):** Used for subtle division lines, card backgrounds, tonal state layers, and pill tag borders.
- **Neutral (`#F7F5F0` — Warm Alabaster Canvas):** The foundational ambient background. Evokes heavy, uncoated fine-art paper.

### Functional Roles & Surface Tiers
- **Canvas Base:** `#F7F5F0` creates an enveloping, warm atmosphere.
- **Surface Elevated:** `#FFFFFF` provides clean separation for product lookbook cards and focal modals while preserving the oat canvas behind them.
- **Muted Text / Metadata:** `#78716C` (Warm Stone) provides legibility without competing with editorial headlines.
- **Interactive States:** Hover effects on dark primary elements transition smoothly to a rich roasted umber (`#292524`), while light neutral containers deepen toward `#EAE5DD`.

## Typography

Typography establishes an editorial cadence balancing literary heritage with clean digital utility:

- **Headlines (Playfair Display):** Conveys editorial sophistication, tailoring, and curated taste. Used exclusively for storytelling, collection titles, and prominent section openers. Never used in heavy, compact UI clusters.
- **Interface & Body (Plus Jakarta Sans):** Delivers clean readability, warm geometry, and modern utilitarian balance across data, body text, wardrobe tags, and form fields.
- **Eyebrows & Metadata (`label-md`, `label-sm`):** Rendered in uppercase with generous letter spacing (`0.08em` to `0.1em`) to replicate luxury magazine folios, collection categorization, and designer attributions.

## Layout & Spacing

The layout is built on a responsive fluid grid with an asymmetric editorial rhythm:

- **Desktop (1024px+):** 12-column fluid grid, `3rem` margins, `1.5rem` gutters. Accommodates lookbook collages, multi-column styling decks, and side-by-side wardrobe comparisons.
- **Tablet (768px - 1023px):** 8-column grid with `2rem` margins, enabling 2-up styling cards with spacious vertical breathing room.
- **Mobile (< 768px):** 4-column grid with `1.25rem` outer margin and `1rem` gutter. Full-bleed and high-ratio imagery are prioritized, leveraging swipeable horizontal carousels that intentionally bleed 16px past screen edges to signal overflow.

### Editorial Image Aspect Ratios
Photography conforms strictly to three high-fashion ratios:
1. **Vertical Lookbook (3:4):** Primary ratio for full-body styling, garment try-on showcases, and outfit assemblies.
2. **Editorial Hero (4:5):** Portrait shots, mood board coverages, and magazine cover feature cards.
3. **Detail Macro (1:1):** Fabric textures, jewelry accents, footwear close-ups, and accessory tags.

## Elevation & Depth

Depth is treated as natural studio lighting falling on soft, physical paper and fine textiles. Avoid stark drop shadows, harsh black tints, and glassy blue glows.

- **Level 0 (Flat Canvas):** Surfaces sit directly on the warm neutral canvas with no shadow, bounded only by whitespace or a 1px boundary in `#EAE5DD`.
- **Level 1 (Curated Cards & Wardrobe Tiles):** Ambient, ultra-diffused shadow tinted with warm umber:
  `box-shadow: 0 4px 20px -2px rgba(28, 25, 23, 0.04), 0 2px 6px -1px rgba(28, 25, 23, 0.02)`.
- **Level 2 (Active Sheets & Hover States):** Lifts elements upward gently:
  `box-shadow: 0 12px 32px -4px rgba(28, 25, 23, 0.07), 0 4px 12px -2px rgba(28, 25, 23, 0.03)`.
- **Level 3 (Stylist Drawers & Overlay Modals):**
  `box-shadow: 0 24px 48px -8px rgba(28, 25, 23, 0.12)`. Paired with a warm, desaturated scrim (`rgba(28, 25, 23, 0.35)` with an ultra-light `2px` backdrop blur).
- **Outlines:** When borders are needed for accessibility or visual containment, use fine hairline borders (`1px solid #E7E2D9`).

## Shapes

The geometric structure balances tailored discipline with gentle, organic curvature:

- **Base Radius (`0.5rem` / `8px`):** Applied to standard interactive cards, input fields, image thumbnails, and inner containers.
- **Large Radius (`rounded-lg` / `1rem` / `16px`):** Applied to primary product showcase cards, styling boards, and modal sheets.
- **Pill Radius (`9999px`):** Applied strictly to category chips, tag selectors, badge indicators, and primary pill action buttons, creating a tactile contrast against structured 3:4 and 4:5 image frames.

## Components

### Buttons
- **Primary Pill:** Background in espresso charcoal (`#1C1917`), typography in warm alabaster (`#F7F5F0`), fully rounded (`rounded-full`). On press, applies a subtle physical compression (`transform: scale(0.98)`).
- **Secondary Accent:** Outline in burnished bronze (`#9A7B56`), text in `#9A7B56`, surface transparent. On hover, background transitions into a 10% bronze wash (`rgba(154, 123, 86, 0.1)`).
- **Ghost / Editorial Link:** Underlined typography with `1.5px` offset, transitioning to bronze on interaction with no bounding box.

### Chips & Pill Tags
- **Filter & Attribute Chips:** Fully rounded (`9999px`), padding `0.375rem 0.875rem`. Unselected state uses an oat surface (`#EAE5DD`) with muted charcoal text (`#44403C`).
- **Selected State:** Espresso charcoal background (`#1C1917`) with alabaster text (`#F7F5F0`) and smooth spring transitions.

### Cards & Lookbook Tiles
- **Stylist Recommendation Card:** Encased in `rounded-lg` (`16px`), rendered in pure white `#FFFFFF` against the canvas background. Houses an edge-to-edge or inset `3:4` aspect ratio image container with a slight `0.5rem` corner radius, a subtle warm umber shadow (Level 1), and bottom-aligned typography pairing Playfair Display titles with Plus Jakarta Sans pricing and meta labels.
- **Color Swatch Clusters:** Mini horizontal clusters of circular swatches (`20px x 20px`) with a fine hairline border indicating fabric tone and garment availability.

### Form Inputs
- **Text Inputs & Search:** Clean, low-contrast fields with subtle `#E7E2D9` borders, `0.5rem` radius, and warm alabaster background (`#FFFFFF`). Placeholder text is rendered in `#A8A29E`.
- **Focused State:** The border transitions to burnished bronze (`#9A7B56`) with a `0 0 0 3px rgba(154, 123, 86, 0.15)` glow ring.

### Checkboxes & Radios
- **Checkboxes:** Square with `4px` rounded corners, warm alabaster fill, espresso border. When checked, fills with `#1C1917` and displays a crisp alabaster check icon.
- **Radio Buttons:** Concentric circles. Selected state features an espresso outer boundary and a bronze (`#9A7B56`) inner focal disc.

### Lists & Atelier Wardrobe Decks
- **Lookbook Accordions:** Borderless rows separated by soft hairline dividers (`#E7E2D9`), expanding downward with fluid height transitions to reveal styling notes, fabric composition, and occasion tags.
- **Occasion Timeline:** Vertical line in `#D8CAB8` connecting time-of-day outfit suggestions, punctuated with bronze node markers.