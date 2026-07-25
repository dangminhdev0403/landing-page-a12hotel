---
name: A21 Celestial Luxury
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#545f73'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f8'
  on-secondary-container: '#586377'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  ice-white: '#F8FAFC'
  gold-leaf: '#D4AF37'
  midnight-slate: '#0F172A'
  glass-border: rgba(15, 23, 42, 0.08)
typography:
  display-lg:
    fontFamily: Poppins
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Poppins
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Poppins
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

This design system embodies the "Celestial Luxury" narrative—a sophisticated fusion of deep nocturnal tones and radiant metallic accents. Targeted at the discerning modern traveler, the UI evokes a sense of quiet exclusivity, precision, and effortless hospitality.

The design style is **Modern Minimalist with Glassmorphic Accents**. It draws inspiration from high-end architectural renderings and luxury automotive interfaces. Key characteristics include:
- **Expansive Whitespace:** Using negative space as a primary design element to convey premium quality.
- **Glassmorphism:** Strategic use of frosted surfaces for overlays and navigation to maintain a sense of depth and spatial awareness.
- **Refined Precision:** Every element is aligned to a strict grid, utilizing thin lines and deliberate typographic hierarchy to guide the user through the "digital concierge" experience.
- **Micro-interactions:** Subtle, slow-motion transitions that mimic the unhurried pace of a luxury resort.

## Colors

The palette is anchored by **Midnight Slate** (#0F172A), providing a grounding, authoritative presence. **Gold Leaf** (#D4AF37) is used sparingly as a high-intent accent for primary calls to action, status indicators, and premium markers, ensuring it retains its psychological value of "prestige."

**Ice White** (#F8FAFC) serves as the canvas, preventing the "clinical" feel of pure white and providing a softer backdrop for the dark typography. Surface hierarchies are built using varying levels of opacity on the Slate tones rather than introducing new hues, maintaining a monochromatic elegance broken only by the warmth of the gold accent.

## Typography

Typography centers on the contrast between the geometric, architectural nature of **Poppins** and the systematic clarity of **Inter**. 

- **Headlines:** Set in Poppins with tight tracking and generous leading. For display text, use a Semi-Bold weight to create a focal point against the minimalist layout.
- **Body:** Inter is used for all long-form content. Its neutral character ensures maximum readability across varied screen densities.
- **Labels:** Small caps with increased letter spacing are used for secondary information (e.g., room categories, dates) to provide a sophisticated, editorial feel without adding visual weight.

## Layout & Spacing

The layout follows a **Fluid Grid System** with substantial margins to mimic the "Apple-level" breathing room. 

- **Desktop:** A 12-column grid with 64px side margins. Large-scale imagery (e.g., room galleries) should break the grid and extend to the screen edge or maintain a consistent 24px internal gutter.
- **Mobile:** A 4-column grid with 20px margins. Content should be vertically stacked with increased padding (32px+) between distinct sections to avoid clutter.
- **Rhythm:** All spacing must be a multiple of 8px. Use 48px or 64px vertical spacing between major sections to emphasize the minimal, airy aesthetic.

## Elevation & Depth

Depth is achieved through **Tonal Layering and Backdrop Blurs** rather than traditional heavy shadows.

- **Level 1 (Base):** Ice White background.
- **Level 2 (Cards):** Pure White (#FFFFFF) surfaces with a 1px border of `midnight-slate` at 5% opacity.
- **Level 3 (Overlays/Nav):** Glassmorphism effect. Use a background blur of 20px and a 60% translucent White fill. 
- **Shadows:** When necessary (e.g., for floating action buttons), use a "Soft Ambient" shadow: `0 12px 40px rgba(15, 23, 42, 0.04)`. It should be almost imperceptible, suggesting the object is hovering slightly above the surface.

## Shapes

The design uses a **Rounded** shape language to soften the geometric lines of the typography.

- **Standard Elements:** Buttons and input fields use a 20px radius (`rounded-lg` equivalent in this system).
- **Cards & Containers:** Main content containers and image cards use a 24px radius (`rounded-xl`).
- **Interactive States:** On hover, shapes do not change radius but can feature a subtle scale-up (1.02x) to provide tactile feedback without disrupting the layout.

## Components

- **Buttons:** 
    - *Primary:* Solid Midnight Slate with Gold text or White text. High-contrast, 20px rounded.
    - *Secondary:* Transparent with a 1.5px Gold-leaf border.
- **Input Fields:** Minimalist style with a bottom-only border that transitions to a full 1px Slate outline upon focus. Place labels above the field in `label-caps`.
- **Cards:** Use a "No-Shadow" approach. Rely on the 24px radius and light border. Room price tags should be anchored to the bottom-right in a small Glassmorphic chip.
- **Chips/Badges:** Use for amenities (e.g., "Spa", "Pool"). These should be low-contrast (Slate at 5% opacity) with 12px Inter medium text to avoid distracting from the main room titles.
- **The Navigation Bar:** A sticky, glassmorphic header that stays transparent until scrolling, then transitions to a frosted blur to maintain content legibility.