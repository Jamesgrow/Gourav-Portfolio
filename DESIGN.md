---
name: Playful Scrapbook Brutalism
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#5c403a'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#906f69'
  outline-variant: '#e5beb6'
  surface-tint: '#ba1b00'
  primary: '#b61b00'
  on-primary: '#ffffff'
  primary-container: '#db3417'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a5'
  secondary: '#745c00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd03d'
  on-secondary-container: '#705900'
  tertiary: '#006949'
  on-tertiary: '#ffffff'
  tertiary-container: '#00855d'
  on-tertiary-container: '#f5fff7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a5'
  on-primary-fixed: '#3f0400'
  on-primary-fixed-variant: '#8e1300'
  secondary-fixed: '#ffe089'
  secondary-fixed-dim: '#edc22e'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#51febc'
  tertiary-fixed-dim: '#20e1a2'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005138'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 84px
    fontWeight: '700'
    lineHeight: 92px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 54px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-mono-lg:
    fontFamily: Space Mono
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-mono-sm:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter-sm: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin-mobile: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 4rem
  sticker-offset-sm: 4px
  sticker-offset-md: 6px
  sticker-offset-lg: 8px
---

## Brand & Style

This design system expresses a vibrant, craft-driven indie portfolio identity. It merges neo-brutalist discipline—such as hard structural borders, high-contrast ink, and solid offset drop shadows—with tactile, scrapbook collage energy. The visual tone is irreverent yet highly intentional, communicating technical mastery, creative grit, and personality without sacrificing user experience or functional hierarchy.

Key style pillars:
- **Neo-Brutalist Tactility:** 2px to 3px solid ink borders paired with razor-sharp, zero-blur hard-drop shadows (`box-shadow: 4px 4px 0px #141414`).
- **Collage & Ephemera:** Stamp badges, rotated sticker labels (-2° to +3° tilts), taped edges, sticky index cards, and layered modular blocks.
- **Oversized & Punchy:** Bold, athletic headlines paired with structured monospace metadata and a super-readable grotesque body.
- **Warm Editorial Grounding:** High-energy accents anchored against warm, organic cream stock instead of sterile digital white.

## Colors

The color architecture is rooted in a tactile print aesthetic. The canvas sits on an off-white cream stock that softens the punch of the hyper-saturated accent tones and solid ink-black strokes.

### Palette Architecture
- **Surface Canvas (Warm Off-White):** `#F5F0E6` serves as the global viewport background.
- **Ink / Structure (Deep Near-Black):** `#141414` defines all borders, primary typography, high-contrast buttons, and hard offset drop shadows.
- **Primary Accent (Punchy Red-Orange):** `#FF4D2E` for hero CTAs, highlight tags, urgent markers, and active states.
- **Secondary Accent (Warm Vibrant Yellow):** `#FFD23F` for sticky-note index cards, playful badge highlights, and hover state transforms.
- **Tertiary Accent (Electric Mint):** `#1EE0A1` for availability badges ("Available for work"), micro-tags, and subtle decorative accents.
- **Quaternary Accent (Electric Blue):** `#2E75FF` reserved for hyperlink states, technical tags, and collage contrast blocks.
- **Card Surface (Clean Paper):** `#FFFFFF` used inside cards to maintain crisp content readability against the `#F5F0E6` canvas.

## Typography

The typographic hierarchy balances expressive geometric brutalism with legible editorial layout:
- **Headlines (Space Grotesk):** Provides mechanical, wide-aperture geometry that feels bold, futuristic, and commanding. Always set with negative tracking to lock characters tightly like a printed headline poster.
- **Body & Editorial (Plus Jakarta Sans):** Offers balanced geometry with warm, open curves to offset the raw, abrasive structure of the headlines, ensuring long-form case studies remain effortless to read.
- **Labels & Metatags (Space Mono):** Used across stickers, badges, timestamps, project role tags, and index-card tabs to reinforce tactile ephemera and precision craft.

## Layout & Spacing

The layout is built on a structured 12-column responsive fluid grid bounded by a max container width of 1280px. Content elements break conventional corporate constraints through overlapping z-indexes, intentional sticker tilts, and offset positioning.

### Responsive Breakpoints & Margin Rules
- **Desktop (≥ 1024px):** 12 columns, 32px gutters, 64px outer margins. Cards can break boundaries with `-12px` to `+16px` positioning margins to create a loose scrapbook overlay.
- **Tablet (768px – 1023px):** 8 columns, 24px gutters, 40px outer margins. Rotations are moderated (maximum ±1.5deg) to maintain comfortable tap areas.
- **Mobile (< 768px):** 4 columns, 16px gutters, 20px outer margins. Cards snap to full column widths; rotated badges remain, but layout items stack vertically without horizontal overflow.

### Rhythm & Alignment
Spacing follows an 8px base rhythm (`8px`, `16px`, `24px`, `32px`, `48px`, `64px`, `96px`). Sections are cleanly separated using either heavy 3px horizontal ink rules (`#141414`) or contrasting background blocks.

## Elevation & Depth

This design system avoids diffused ambient shadows, blurred drop shadows, or translucent glassmorphism entirely. Depth is created through crisp physical layering and hard-edged ink offsets.

### Depth Rules
- **Level 0 (Flat Ground):** Background `#F5F0E6`. Elements resting flush with no elevation.
- **Level 1 (Default Cards & Interactive Elements):** Solid border `2.5px solid #141414` with a hard drop shadow: `box-shadow: 4px 4px 0px #141414`.
- **Level 2 (Active Stickers & Hover States):** Solid border `3px solid #141414` with an expanded shadow: `box-shadow: 6px 6px 0px #141414`. On interaction, elements translate `-2px, -2px` to meet the expanded shadow.
- **Pressed / Active State:** On `:active`, elements translate down and right (`transform: translate(4px, 4px)`), collapsing the shadow to `0px 0px 0px #141414`, mimicking a mechanical stamp or physical button depression.
- **Overlap Layering:** Sticker tags and sticky notes use explicit `z-index` layering (`z-10`, `z-20`) to overlap container borders.

## Shapes

The shape language uses subtle softness constrained by hard ink:
- **Base Geometry:** Standard components (cards, dialogs, media containers) use a subtle `0.25rem` (4px) border radius to eliminate digital sharpness while preserving heavy blocky neo-brutalist presence.
- **Stickers & Micro-Tags:** Badges and pill tags can use full pill curvature (`9999px`) or clipped ticket-edge notches, framed with `2px solid #141414` to evoke physical die-cut vinyl stickers.
- **Rotations:** Dynamic sticker badges and index labels feature standard preset transforms: `rotate(-2deg)`, `rotate(1.5deg)`, or `rotate(-3deg)`.

## Components

### Buttons
- **Primary Action:** Solid background `#FF4D2E`, text `#FFFFFF`, border `2.5px solid #141414`, `box-shadow: 4px 4px 0px #141414`, font Space Grotesk Bold. Hover: transforms `translate(-2px, -2px)` with shadow expanding to `6px 6px 0px #141414`. Active: `translate(4px, 4px)` with shadow `0px 0px 0px`.
- **Secondary Action:** Background `#FFFFFF` or `#FFD23F`, text `#141414`, border `2.5px solid #141414`, `box-shadow: 4px 4px 0px #141414`.

### Project & Portfolio Cards
- Surface `#FFFFFF` encased in a `2.5px solid #141414` border with `box-shadow: 6px 6px 0px #141414`.
- Image frames inside cards feature an inner `2px solid #141414` border with an optional grayscale-to-color hover transition.
- Case study cards incorporate top-right or top-left protruding "tape" strips (semi-transparent beige or yellow bars) or rotated mono stickers.

### Sticky Note Index Cards
- Background `#FFD23F` or `#1EE0A1`, border `2.5px solid #141414`, rotated at `-1.5deg`.
- Header set in Space Mono bold uppercase with a dashed horizontal divider (`border-top: 2px dashed #141414`).
- Used for quick callouts, design philosophies, current status, or testimonial quotes.

### Chips & Badges (Stickers)
- Die-cut appearance: background `#1EE0A1` (for status), `#2E75FF` (for tech tags), or `#FFD23F`.
- Wrapped in `2px solid #141414` with a hard `2px 2px 0px #141414` offset.
- Set in Space Mono (12px), uppercase, with slight random rotations (`-2deg` to `+2.5deg`).

### Input Fields & Contact Form
- Background `#FFFFFF`, border `2.5px solid #141414`, padding `14px 18px`.
- Focus state: `box-shadow: 4px 4px 0px #FF4D2E` (or `#141414`), outline: none.
- Placeholder text in Plus Jakarta Sans with 50% opacity ink.

### Selection Controls (Checkboxes & Radios)
- **Checkbox:** Square, border `2.5px solid #141414`, border-radius 2px. Checked: fill `#FF4D2E` with a bold black checkmark and `2px 2px 0px #141414` shadow.
- **Radio:** Rounded circle, border `2.5px solid #141414`. Selected: inner solid black circle surrounded by `#FFD23F`.