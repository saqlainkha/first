---
name: Academic Prestige Collegiate
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7b'
  primary: '#001126'
  on-primary: '#ffffff'
  primary-container: '#12263f'
  on-primary-container: '#7b8eac'
  inverse-primary: '#b4c8e8'
  secondary: '#755b00'
  on-secondary: '#ffffff'
  secondary-container: '#fed255'
  on-secondary-container: '#735a00'
  tertiary: '#00140b'
  on-tertiary: '#ffffff'
  tertiary-container: '#002c1c'
  on-tertiary-container: '#1e9f72'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#b4c8e8'
  on-primary-fixed: '#061c35'
  on-primary-fixed-variant: '#354862'
  secondary-fixed: '#ffe08e'
  secondary-fixed-dim: '#ecc246'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
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
  space-2xl: 4rem
---

## Brand & Style

The design system projects academic rigor, institutional prestige, and contemporary clarity. It balances centuries-old collegiate dignity with modern educational accessibility. Designed primarily for prospective students, faculty, alumni, and parents, the interface fosters trust, forward-looking ambition, and institutional honor.

The visual style blends **Editorial Neo-Collegiate** with **Modern Enterprise Cleanliness**:
- Crisp, luminous white card surfaces set against a serene, cool stone backdrop.
- Authoritative typography that mirrors academic publications and scholarly journals.
- Measured, generous whitespace inspired by institutional architectural campuses.
- Dignified collegiate elements: gilded accents, bespoke micro-badges, and refined structural borders rather than heavy, nostalgic clutter.

## Colors

The palette establishes an immediate academic hierarchy through deep tradition and calculated energetic accents:

- **Primary (`#12263F` - Deep Navy Blue):** Anchors headers, primary brand marks, hero footers, and foundational UI scaffolding. Symbolizes heritage, intellectual focus, and institutional integrity.
- **Secondary (`#C9A227` - Collegiate Gold):** Reserved for academic honors, decorative rules, verified credentials, program highlights, and fine framing accents. Must be used deliberately to retain its feeling of distinction.
- **Tertiary (`#059669` - Emerald Green):** The high-conversion conversion action color, exclusively engineered for direct admission points, 'Apply Now' triggers, scholarship acceptance, and interactive progress steps.
- **Neutral (`#F4F6F9` - Light Canvas Grey):** The soft foundation across all full-bleed page layouts, reducing eye fatigue and separating interactive white surfaces (`#FFFFFF`) from the background without harsh boundaries.
- **Text & Borders:** Body text uses `#2D3748` for high legibility; structural borders use `#E2E8F0` to maintain soft surface boundaries.

## Typography

The pairing creates an editorial cadence: **Playfair Display** provides scholarly authority across titles and landmark headers, while **Inter** delivers clean legibility for dense course catalogs, student portals, and forms.

- All display and headline tracking is set slightly tight to ensure editorial poise.
- Body text maintains an open line height (`1.5` to `1.55`) to facilitate long-form reading across faculty biographies and academic prospectuses.
- Small labels, academic badges, and section eyebrow titles should use `label-sm` with uppercase styling and expanded tracking (`letter-spacing: 0.04em`).

## Layout & Spacing

The layout is built on an adaptive 12-column grid anchored by generous vertical rhythm:

- **Desktop (≥ 1024px):** 12-column grid, 1.5rem (`24px`) gutters, outer margin of 3rem (`48px`), max container width capped at `1280px` for optimal reading width.
- **Tablet (768px – 1023px):** 8-column grid, 1.25rem (`20px`) gutters, outer margin of 2rem (`32px`).
- **Mobile (≤ 767px):** 4-column fluid grid, 1rem (`16px`) gutters, outer canvas margin of 1.25rem (`20px`).

Spacing follows an expansive cadence. Content modules use `space-xl` and `space-2xl` for section separation, evoking the calm, unhurried presence of physical campus grounds.

## Elevation & Depth

Visual depth is achieved through **Tonal Layers** combined with **Ambient Navy-Tinted Shadows**:

- **Canvas Base:** `#F4F6F9` provides a calm, unified ground.
- **Card Surface:** `#FFFFFF` stands out cleanly against the neutral ground with a 1px border of `#E2E8F0`.
- **Resting Elevation:** `0 4px 16px -2px rgba(18, 38, 63, 0.06)`, applying a subtle navy tint instead of dead neutral black.
- **Hover / Interactive Elevation:** `0 12px 28px -4px rgba(18, 38, 63, 0.12)`, accompanied by a subtle upward translation (`translate-y: -2px`).
- **Modal / Flyout Elevation:** `0 20px 40px -8px rgba(18, 38, 63, 0.20)` alongside a diffused backdrop blur (`backdrop-filter: blur(8px)` with `rgba(18, 38, 63, 0.4)` overlay).

## Shapes

The design system incorporates intentional, gentle curves to soften its traditional academic identity:

- **Base Radius (`rounded-md`):** `0.5rem` (8px) for buttons, inputs, tags, and small utility triggers.
- **Surface Radius (`rounded-xl`):** `1rem` (16px) for standard program cards, news blocks, and feature modals.
- **Hero & Shell Radius (`rounded-2xl`):** `1.5rem` (24px) for prominent landing hero containers, callout banners, and campus image frames.
- **Badges & Pills:** Fully rounded (`9999px`) for application deadlines, status badges, and academic terms.

## Components

### Buttons
- **High-Conversion CTA ('Apply Now'):** Solid Emerald Green (`#059669`) with white text, font weight `600`, padding `0.875rem 1.75rem`, rounded-xl (`1rem`). On hover: `#047857` with slight elevation bloom.
- **Primary Institutional:** Deep Navy (`#12263F`) with white text. Used for portal logins, prospectus downloads, and primary navigation actions.
- **Secondary / Academic:** Outlined button in `#12263F` with 1.5px border, transparent background, and `#12263F` text; shifts to a soft navy wash on hover.
- **Honorary Accent:** Collegiate Gold border or subtle `#C9A227` text link with arrow icon for faculty listings and award overviews.

### Cards
- Pure white background (`#FFFFFF`) framed by a subtle 1px border (`#E2E8F0`) and resting elevation.
- Program Cards feature a top 3px accent line in either Deep Navy or Collegiate Gold to categorize disciplines.
- Internal padding is set to `1.5rem` (`space-lg`) on mobile and `2rem` on desktop.

### Chips & Badges
- **Status & Accreditations:** Pill-shaped (`rounded-full`), padded `0.25rem 0.75rem`.
- **Honor Chips:** `#C9A227` tinted background (`rgba(201, 162, 39, 0.12)`) with `#8F7113` text and bold tracking.
- **Urgent Deadlines:** Soft amber or emerald tone depending on positive or approaching admission cycle states.

### Input Fields
- White surface, 1px border (`#CBD5E1`), rounded-md (`0.5rem`), padding `0.75rem 1rem`.
- Focus state creates a 2px outer ring of `#12263F` with smooth transition, maintaining accessibility and clear contrast.

### Checkboxes & Radios
- Square with 4px border radius for checkboxes; circular for radios.
- Inactive: `#CBD5E1` border with clean white interior.
- Checked: Deep Navy (`#12263F`) fill with white checkmark glyph or center dot.

### Lists
- Academic directory lists feature bottom dividing borders in `#E2E8F0`, padding of `1rem 0`, with subtle gold left-notch indicators on hover.

### Specialized Collegiate Components
- **Institutional Crest Lockup:** High-contrast positioning on Deep Navy headers or clean white canvas, paired with serif brand nameplates.
- **Honorary Banner:** Deep Navy background with subtle Collegiate Gold border detailing, used for major announcements, convocation dates, and scholarship notices.