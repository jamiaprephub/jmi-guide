---
name: Elite Scholastic SaaS
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#d7c1c4'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#9f8c8f'
  outline-variant: '#524346'
  surface-tint: '#ffb1c3'
  primary: '#ffb1c3'
  on-primary: '#541e2e'
  primary-container: '#3d0b1c'
  on-primary-container: '#ba7183'
  inverse-primary: '#8c4a5b'
  secondary: '#ffb0c9'
  on-secondary: '#640035'
  secondary-container: '#8d134f'
  on-secondary-container: '#ff9abd'
  tertiary: '#e2b5ff'
  on-tertiary: '#451d61'
  tertiary-container: '#31054e'
  on-tertiary-container: '#a074be'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd9e0'
  primary-fixed-dim: '#ffb1c3'
  on-primary-fixed: '#390819'
  on-primary-fixed-variant: '#6f3444'
  secondary-fixed: '#ffd9e3'
  secondary-fixed-dim: '#ffb0c9'
  on-secondary-fixed: '#3e001e'
  on-secondary-fixed-variant: '#890f4c'
  tertiary-fixed: '#f3daff'
  tertiary-fixed-dim: '#e2b5ff'
  on-tertiary-fixed: '#2e014b'
  on-tertiary-fixed-variant: '#5d357a'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
  oxford-burgundy: '#3D0B1C'
  electric-plum: '#A1265E'
  soft-lavender: '#E0B0FF'
  deep-indigo-accent: '#1A1A2E'
  glass-border: rgba(161, 38, 94, 0.2)
  surface-card: rgba(255, 255, 255, 0.03)
typography:
  display-hero:
    fontFamily: EB Garamond
    fontSize: 72px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: EB Garamond
    fontSize: 44px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
  code:
    fontFamily: Geist Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is engineered to evoke a sense of academic excellence combined with cutting-edge technological precision. It targets high-achieving students who seek a professional, distraction-free environment that feels both prestigious and technologically superior.

The aesthetic follows a **Premium Dark-Mode Glassmorphism** style. It leverages the depth and sophistication of dark, layered surfaces found in elite developer tools, tempered with the warmth of a rich burgundy palette. The interface utilizes subtle noise textures to give digital surfaces a tactile, paper-like quality, while aurora-style blurs provide a sense of dynamic energy. The result is an "Elite Student-First" experience: authoritative like a physical library, but fast and fluid like a modern productivity suite.

## Colors

This design system utilizes a deep, nocturnal palette designed for long study sessions without eye strain. 

- **Primary (Oxford Burgundy):** Used for foundational backgrounds and deep tonal layers.
- **Secondary (Electric Plum):** The primary interactive color, used for CTA buttons, progress indicators, and active states.
- **Tertiary (Soft Lavender):** Used sparingly for high-contrast accents, text highlights, and the "bloom" in aurora gradients.
- **Background Strategy:** The base layer is a near-black `#0A0A0B`. Over this, we apply radial gradients of `Oxford Burgundy` and `Deep Indigo` with a 2% grain texture overlay to create "Aurora" backgrounds.
- **Glass Surfaces:** Containers use `surface-card` with a backdrop blur of 12px-20px and a 1px solid border using `glass-border` or low-opacity white.

## Typography

The typography strategy relies on the tension between the classical **EB Garamond** and the hyper-modern **Geist**.

- **Headlines:** Use EB Garamond for all major headings. The high-contrast serifs provide a "Scholastic Elite" feel. Use optical sizing where available and keep tracking tight on larger sizes.
- **Body & UI:** Geist (or Inter as fallback) provides a technical, legible counterpart. It should be typeset with generous line-height (1.6x) to ensure readability during dense study material.
- **Labels:** Small labels and overlines should use Geist with increased letter spacing and uppercase styling to denote hierarchy without increasing font size.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for core content to maintain a premium, editorial feel, while components within the grid utilize fluid internal spacing.

- **The Bento Grid:** For dashboards and feature sections, use a Bento-style layout. This consists of varied-size "tiles" (cards) that snap to a 12-column grid.
- **Whitespace:** Emulate the "Stripe" aesthetic by utilizing vertical gaps of 120px+ between major landing page sections. 
- **Internal Spacing:** Components should use an 8px-based scale for padding. Cards typically feature 32px of internal padding to feel spacious and high-end.
- **Responsive Flow:** On mobile, the 12-column grid collapses to a single column, and the section gaps reduce to 64px.

## Elevation & Depth

Depth is not communicated through heavy shadows, but through **Tonal Layering and Translucency**.

1.  **Level 0 (Base):** Deep `#0A0A0B` with subtle noise and aurora blurs.
2.  **Level 1 (Surface):** Glassmorphic panels with 12px backdrop blur and 3% white fill. These surfaces "float" with a very soft, large-radius shadow (60px blur, 0.2 opacity black).
3.  **Level 2 (Interactive):** When hovered, glass surfaces increase their border opacity or gain a subtle outer glow using the `Electric Plum` color.
4.  **Accents:** Use 1px "internal strokes" (inner borders) to define edges sharply, mimicking the precision of a high-end physical device.

## Shapes

The shape language is sophisticated and "squircle-adjacent." 

- **Cards & Containers:** Use a base radius of 16px. Large bento-style sections may scale up to 24px to emphasize their containing nature.
- **Interactive Elements:** Buttons and input fields follow a 12px radius, ensuring they feel distinct from the larger layout containers.
- **Iconography:** Use light-weight (2pt) icons with rounded terminals to match the Geist typography.

## Components

- **Interactive Cards:** Use the Glassmorphic style. On hover, the 1px border should transition from `glass-border` to a brighter `Electric Plum`. Implement a subtle "shine" gradient that follows the mouse cursor.
- **Buttons:**
    - *Primary:* Solid `Electric Plum` with white text. Apply a subtle top-down gradient and a 1px inner highlight on the top edge.
    - *Secondary:* Glass background with white text and a 1px border.
- **Bento Grid:** Use varied aspect ratios (1x1, 2x1, 2x2). Each cell in the grid should have its own subtle aurora blur in the background to create visual interest.
- **Input Fields:** Dark, recessed backgrounds with `Soft Lavender` focus states. Placeholders should be low-contrast (40% opacity).
- **Progress Indicators:** Use thin, high-glow lines in `Soft Lavender` to represent student progress, contrasting against the dark `Oxford Burgundy` backgrounds.