---
name: Haute Editorial AI
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f2'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e3e1'
  on-surface: '#1a1c1b'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#665d55'
  on-secondary: '#ffffff'
  secondary-container: '#eaddd4'
  on-secondary-container: '#6a615a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#241a00'
  on-tertiary-container: '#a08000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ede0d7'
  secondary-fixed-dim: '#d0c4bb'
  on-secondary-fixed: '#201a15'
  on-secondary-fixed-variant: '#4d453f'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e1'
typography:
  headline-xl:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Bodoni Moda
    fontSize: 30px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0.01em
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
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.12em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system translates the restrained authority of vintage and contemporary print publications—such as *Vogue*, *SSENSE*, and *W Magazine*—into a responsive, touch-first mobile interface. Designed for discerning tastemakers and personal styling clients, the interface evokes the quiet confidence of an atelier fitting room combined with algorithmic precision.

The core aesthetic combines **Editorial Minimalism** with **Warm Tactile Layering**:
- Uncluttered compositions with intentional negative space, avoiding aggressive modern app tropes (such as noisy gradients or heavy drop shadows).
- High visual contrast between hyper-legible body details and statuesque display serif headers.
- Restrained, tactile touch surfaces utilizing hairline borders and matte, textured surfaces rather than gloss or hyper-saturated accents.
- Subtle golden nuances reserved exclusively for curation milestones, AI confidence scores, and luxury tier indications.

## Colors

The palette grounds the interface in classic print materiality: natural archival paper, deep carbon ink, and soft structural neutrals.

- **Primary (`#111111`)**: Deep espresso black. Applied to dominant titles, primary functional buttons, and key structural frames. It ensures absolute clarity without the harshness of pure `#000000`.
- **Secondary (`#8C827A`)**: Muted sand-taupe. Dedicated to metadata, editorial attributions, secondary captions, and disabled states.
- **Tertiary (`#D4AF37`)**: Muted satin gold. Used sparingly for curated styling badges, AI match quality indicators, premium recommendations, and active selection pips.
- **Neutral Canvas (`#FBFBF9`)**: Warm cream / off-white base. Acts as the primary viewport surface, simulating untreated linen and premium heavyweight paper stocks.
- **Surface Variant (`#F5F5F0`)**: Secondary container background for outfit grids, fitting-room panels, and card backdrops.
- **Border / Hairline Neutral (`#EAE7E2`)**: Structural boundary lines providing tactile compartmentalization without optical heaviness.

## Typography

The typographic hierarchy establishes tension between the haute-couture heritage of **Bodoni Moda** and the contemporary, engineered geometry of **Plus Jakarta Sans**.

- **Editorial Headings (`Bodoni Moda`)**: High-contrast strokes, refined vertical axes, and sharp serifs simulate classic editorial mastheads and runway program guides. Used strictly for section titles, article headers, stylist critiques, and seasonal collection themes.
- **Functional Interface & Reading (`Plus Jakarta Sans`)**: Neutral, slightly rounded grotesque rendering delivers immediate legibility at small scale for e-commerce listings, garment metrics, sizing tables, and conversational stylist prompts.
- **Case Sensitivity & Tracking**: Display headings utilize sentence case or small-caps for natural rhythm. High-tier subheaders, category flags, and pills use `label-sm` or `label-md` in full uppercase with expanded letter-spacing (`0.08em` to `0.12em`) to echo luxury branding conventions.

## Layout & Spacing

The layout is built around a mobile-first fluid grid that favors generous breathing room and asymmetrical editorial pacing:

- **Grid Architecture**: Mobile screens operate on a 4-column fluid layout with a base gutter of `1rem` and outer margins of `1.25rem`. Tablet expands to 8 columns (`1.5rem` gutter), and desktop scales to 12 columns constrained to a max-width of `1280px` centered canvas with `3rem` margins.
- **Editorial Asymmetry**: Outfits and lookbook spreads lean into deliberate editorial rhythm—full-bleed hero snapshots alternate with 2-column detail breakouts (e.g., fabric close-ups, palette chips).
- **Safe Zones & Navigation Clearance**: The bottom navigation is anchored with explicit touch margins, demanding a permanent `space-xl` (40px) clearance padding on scroll containers to prevent action overlap.

## Elevation & Depth

Visual hierarchy does not rely on saturated, heavy drop shadows. Depth is communicated strictly through surface layering, micro-borders, and diffused ambient illumination.

- **Low-Contrast Hairlines**: Depth begins with `1px solid #EAE7E2`. Cards, bottom sheets, and sticky navigation bars rely on this crisp demarcation line to demarcate spatial layers against `#FBFBF9` canvas backgrounds.
- **Tonal Stepping**: 
  - Level 0 (Base Canvas): `#FBFBF9`
  - Level 1 (Cards, Lookbook Cells): `#FFFFFF` or `#F5F5F0`
  - Level 2 (Sheets, Modals, Overlays): Pure `#FFFFFF` surface with micro-borders.
- **Ambient Veil (Shadows)**: When floating modules or interactive look cards lift upon scroll, they cast an ethereal, low-contrast shadow: `0 8px 32px -4px rgba(17, 17, 17, 0.04), 0 2px 8px -2px rgba(17, 17, 17, 0.02)`.
- **Frosted Backdrop Surfaces**: Sticky headers and floating bottom navigations utilize a translucent veil of `rgba(251, 251, 249, 0.85)` coupled with `backdrop-filter: blur(16px)` to maintain connection with garments passing beneath.

## Shapes

The design system employs a refined curvature profile (`roundedness: 2`) designed specifically for luxury curation:

- **Lookbook & Garment Containers**: Fixed at `16px` (`rounded-lg` / `1rem`), providing a soft, tactile frame that flatters editorial portrait photography.
- **Pill Badges & Functional Tags**: Full pill curvature (`9999px`) for styling metadata, mood categorization, sizing tags, and AI attributes.
- **Primary CTA Buttons**: Curated at `12px` to `16px` to maintain a structural, architectural silhouette that avoids playful balloon aesthetics.
- **Dividers & Badges**: Thin geometry, flat ends, and clean vertical hairpins for editorial index indicators.

## Components

### Buttons
- **Primary Button**: Solid `#111111` background, `#FBFBF9` text, `16px` border-radius, `48px` minimum touch height. Font style set to `label-lg` in uppercase. Micro-hover/press transitions to `opacity: 0.9` with gentle scale down (`0.99`).
- **Secondary Button**: Outlined in `1px solid #111111`, transparent background, `#111111` typography.
- **Tertiary / Curate Action**: Outlined in `1px solid #EAE7E2`, `#F5F5F0` background, `#8C827A` text, transforming to `#111111` on active state.

### Badges & Pill Tags
- **AI Stylist Score Pill**: `#FFFFFF` background, `1px solid #D4AF37`, containing a gold `#D4AF37` spark glyph alongside a numerical percentage in `label-sm`.
- **Attribute & Style Filter Chips**: Background `#F5F5F0`, text `#111111`, no shadow. When active, shifts to solid `#111111` with `#FBFBF9` text.

### Cards (Lookbook & Garment)
- **Garment Container**: `#FFFFFF` background, `16px` radius, `1px solid #EAE7E2` border. Aspect ratios strictly editorial (`3:4` or `4:5`). Images feature subtle center focal framing with minimal internal margins (`12px`).
- **Editorial Advice Box**: Warm `#F5F5F0` fill, `16px` radius, left border accent of `2px solid #D4AF37` for algorithmic personal notes.

### Form Inputs & Text Fields
- **Search & Prompts**: Minimal pill or `12px` rounded inputs with background `#FFFFFF` and border `1px solid #EAE7E2`. Placeholder styled in `body-md` using `#8C827A`. Focus ring transitions border to `#111111` without bright browser halos.

### Selection Controls (Checkboxes & Radios)
- **Radio Buttons**: Concentric circles; outer ring `#111111` (`18px` diameter), inner dot `#111111` (`8px` diameter) buffered by a `#FBFBF9` ring.
- **Color Swatches**: Circular `28px` discs encased in a `1px solid #EAE7E2` border; active swatch features an outer offset ring in `#111111`.

### Navigation & Tabs
- **Bottom Navigation Bar**: Fixed at base, backdrop blur `16px` over `rgba(251, 251, 249, 0.9)`, border top `1px solid #EAE7E2`. Icons rendered in delicate `1.5px` strokes; active item marked by a tiny `#111111` dot below the glyph.
- **Segmented Lookbook Tabs**: Text-only navigation in `label-lg`. Inactive tabs render in `#8C827A`. Active tab is `#111111` with an underline of `1.5px solid #111111` extending precisely to the label width.