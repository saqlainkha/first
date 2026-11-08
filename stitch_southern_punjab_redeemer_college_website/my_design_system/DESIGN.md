---
name: My Design System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d7dae3'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3fc'
  surface-container: '#ebedf7'
  surface-container-high: '#e6e8f1'
  surface-container-highest: '#e0e2eb'
  on-surface: '#181c22'
  on-surface-variant: '#414753'
  inverse-surface: '#2d3037'
  inverse-on-surface: '#eef0fa'
  outline: '#717785'
  outline-variant: '#c1c6d5'
  surface-tint: '#005db8'
  primary: '#005cb8'
  on-primary: '#ffffff'
  primary-container: '#1275e2'
  on-primary-container: '#000512'
  inverse-primary: '#aac7ff'
  secondary: '#465f88'
  on-secondary: '#ffffff'
  secondary-container: '#b6d0ff'
  on-secondary-container: '#3f5881'
  tertiary: '#9a4600'
  on-tertiary: '#ffffff'
  tertiary-container: '#c05900'
  on-tertiary-container: '#0d0300'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aac7ff'
  on-primary-fixed: '#001b3e'
  on-primary-fixed-variant: '#00458d'
  secondary-fixed: '#d6e3ff'
  secondary-fixed-dim: '#aec7f7'
  on-secondary-fixed: '#001b3d'
  on-secondary-fixed-variant: '#2d476f'
  tertiary-fixed: '#ffdbc9'
  tertiary-fixed-dim: '#ffb68c'
  on-tertiary-fixed: '#321200'
  on-tertiary-fixed-variant: '#763400'
  background: '#f9f9ff'
  on-background: '#181c22'
  surface-variant: '#e0e2eb'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

# Design System

## Brand & Style
The design system adopts a **Corporate / Modern** aesthetic styled with a "fidelity" variant, aiming to project reliability, precision, and high-performance clarity. The visual tone is professional, grounded, and approachable, designed to build immediate trust with users across enterprise and consumer contexts. 

- **Aesthetic:** Clean, structured, highly legible, and purposeful.
- **Tone:** Authoritative yet accessible; prioritizes function and clarity above decorative distraction.
- **Emotional Response:** Competence, reliability, focus, and ease of use.

## Colors
The color palette is built for clarity and contrast within a light color mode environment. The primary accent is a crisp, professional blue, supported by muted slate secondary tones and warm tertiary highlights.

- **Primary (`#1275e2`):** Used for key interactive elements, primary buttons, active states, and focus indicators.
- **Secondary (`#5f78a3`):** Provides balanced support for secondary actions, tags, and supportive UI chrome.
- **Tertiary (`#c55b00`):** Acts as a deliberate accent color for calls to action, important notifications, or focal points that require immediate attention.
- **Neutral (`#74777f`):** Forms the backbone for structural text, borders, and background surfaces, ensuring high readability and reducing visual fatigue.

## Typography
**Inter** is utilized across all headline, body, and label roles for its exceptional legibility, neutral geometric structure, and crisp rendering across diverse screen densities.

- **Scale:** Modular typographic scale ranging from 11px micro-labels up to 32px prominent headlines.
- **Weights:** Restricted primarily to regular (400) for body copy, medium (500) for interactive labels, and semi-bold (600) for structural headlines to maintain a clean hierarchical rhythm.

## Layout & Spacing
The layout system follows a structured **Fluid grid** model with proportional margins and gutters designed to adapt seamlessly across form factors.

- **Spacing Rhythm:** Built on a reliable 4px/8px base scale (`space-xs` to `space-xl`), ensuring predictable, harmonious vertical and horizontal alignment.
- **Margins & Gutters:** Standard outer canvas margins are set to `1.5rem` with `1rem` column gutters, transitioning smoothly between mobile, tablet, and desktop viewports.

## Elevation & Depth
Elevation is expressed primarily through **Tonal layers** and subtle, low-opacity ambient shadows to delineate content groupings without creating heavy visual clutter.

- **Surfaces:** Utilize tonal shifts in neutral backgrounds to communicate hierarchical depth (e.g., cards floating on base canvases).
- **Shadows:** Kept minimal and diffused to preserve the modern, flat-leaning corporate aesthetic while maintaining clear interactive affordances for elevated components like modals and dropdowns.

## Shapes
The shape language employs a **Rounded** profile (Level 2), giving standard UI elements a approachable, modern corner radius of `0.5rem`, with larger containers scaling up to `1rem` or `1.5rem`.

- **Buttons & Inputs:** Feature a consistent `0.5rem` corner radius for a friendly yet professional tactile feel.
- **Cards & Modals:** Scale up their rounding to create soft, contained containment zones that harmonize with the overall modern layout philosophy.

## Components
Components are designed for clarity, high accessibility, and tactile feedback.

- **Buttons:** Solid primary buttons use `#1275e2` with rounded corners (`0.5rem`), clear Inter label typography, and high-contrast text. Secondary and text variants rely on neutral borders or subtle background tinting.
- **Inputs:** Form fields feature crisp neutral borders (`#74777f`), clear inner padding matching the spacing scale, and prominent focus states in the primary accent color.
- **Cards:** Contained within soft rounded surfaces, featuring clean internal padding and subtle tonal separation.
- **Checkboxes & Radios:** Use the primary accent color for checked/selected states with clear high-contrast indicators.
- **Chips & Lists:** Compact elements utilizing secondary/neutral tones for tagging, filtering, and structured data presentation.