---
name: Obsidian Kinetic
colors:
  surface: '#111318'
  surface-dim: '#111318'
  surface-bright: '#37393e'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c20'
  surface-container: '#1e2024'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e8'
  on-surface-variant: '#d7c3b2'
  inverse-surface: '#e2e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#9f8e7e'
  outline-variant: '#524438'
  surface-tint: '#ffb86e'
  primary: '#ffb86e'
  on-primary: '#492900'
  primary-container: '#c68132'
  on-primary-container: '#402300'
  inverse-primary: '#8a5100'
  secondary: '#bac3ff'
  on-secondary: '#202b66'
  secondary-container: '#394481'
  on-secondary-container: '#a9b4f9'
  tertiary: '#7bd0fe'
  on-tertiary: '#003549'
  tertiary-container: '#3e9ac5'
  on-tertiary-container: '#002d40'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcbd'
  primary-fixed-dim: '#ffb86e'
  on-primary-fixed: '#2c1600'
  on-primary-fixed-variant: '#693c00'
  secondary-fixed: '#dee0ff'
  secondary-fixed-dim: '#bac3ff'
  on-secondary-fixed: '#061451'
  on-secondary-fixed-variant: '#37427e'
  tertiary-fixed: '#c3e8ff'
  tertiary-fixed-dim: '#7bd0fe'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c68'
  background: '#111318'
  on-background: '#e2e2e8'
  surface-variant: '#333539'
  text-primary: '#e6edf3'
  text-muted: '#93a09a'
  surface-elevated: '#161b22'
  border-glass: rgba(230, 237, 243, 0.1)
  accent-glow: rgba(193, 125, 46, 0.35)
typography:
  hero-title:
    fontFamily: Poppins
    fontSize: 92px
    fontWeight: '700'
    lineHeight: '1.02'
    letterSpacing: -0.02em
  hero-title-mobile:
    fontFamily: Poppins
    fontSize: 46px
    fontWeight: '700'
    lineHeight: '1.1'
  section-title:
    fontFamily: Poppins
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  component-h3:
    fontFamily: Poppins
    fontSize: 21px
    fontWeight: '600'
    lineHeight: '1.4'
  body-large:
    fontFamily: Roboto
    fontSize: 17px
    fontWeight: '400'
    lineHeight: '1.7'
  body-standard:
    fontFamily: Roboto
    fontSize: 16.5px
    fontWeight: '400'
    lineHeight: '1.85'
  interface-ui:
    fontFamily: Roboto
    fontSize: 14.5px
    fontWeight: '500'
    lineHeight: '1.7'
  navigation:
    fontFamily: Roboto
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.2'
  eyebrow-mono:
    fontFamily: Roboto Mono
    fontSize: 12.5px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  caption-label:
    fontFamily: Roboto
    fontSize: 11px
    fontWeight: '400'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  section-v: 120px
  container-max: 1180px
  gutter-md: 24px
  margin-page: 40px
  card-padding: 30px
  stack-gap: 16px
---

## Brand & Style

This design system is a sophisticated fusion of **Technical Minimalism** and **Glassmorphism**, specifically engineered for a high-end engineering or developer portfolio. It transitions the existing "blueprint" aesthetic into a high-performance dark environment, evoking a sense of looking at a premium terminal or a sophisticated aerospace interface.

The brand personality is **Precise, Luminescent, and Deep**. It leverages a "Sleek Technical" style where depth is not created by physical shadows, but by light transmission through layers of semi-transparent material. The atmosphere is quiet and focused, punctuated by "kinetic" energy from glowing amber accents that represent active signals within a dark void.

**Key Visual Principles:**
- **Luminosity over Mass:** Use glows and translucency rather than heavy shadows to indicate hierarchy.
- **Atmospheric Depth:** Utilize the primary indigo accent as a "fog" or radial background glow to prevent the dark mode from feeling flat or "crushed."
- **Network Aesthetic:** Maintain the established 3D/network cues through thin, high-precision lines and interactive "active" states.

## Colors

The palette is anchored by a deep charcoal-slate base, providing a high-contrast foundation for technical clarity.

- **Primary Amber (#c17d2e):** Retained for brand continuity but treated as a light source. In this dark context, it should be used for critical focus points and "active" signals.
- **Secondary Indigo (#55609e):** Used as a structural depth color—best applied in large-scale radial gradients behind content or as subtle fills for complex UI elements to provide "air."
- **Neutrals:** The background is a solid `#0a0c10`, while surfaces use a slightly lighter `#161b22` to create separation. 
- **Typography:** Text is strictly off-white (`#e6edf3`) to reduce eye strain and "blooming" effects on dark backgrounds, with secondary info pulled back into a muted teal-grey.

**Implementation Note:** When using the Primary Accent for interactive states, apply a subtle `box-shadow` or `filter: drop-shadow` using the `accent-glow` variable to simulate a light-emitting diode (LED) effect.

## Typography

The typography system balances the geometric warmth of **Poppins** for hierarchy and the clinical legibility of **Roboto** for data and prose. 

**Hierarchical Rules:**
- **Display:** Large headlines use Poppins with tight tracking and leading to create a "blocky" architectural feel.
- **Technical Layers:** Use Roboto Mono for all metadata, tags, and eyebrow labels to reinforce the "engineering schematic" narrative.
- **Reading:** Maintain generous line-heights (1.85x) for body text to ensure high legibility against the dark background, preventing "letter-crowding" which is common in dark mode.
- **Scaling:** Hero titles must use fluid scaling (`clamp`) to maintain visual impact on wide monitors without breaking on mobile.

## Layout & Spacing

This design system uses a **Fixed Grid** approach for its primary content containers to maintain the "schematic" look, while utilizing fluid internal spacing for component layout.

- **Grid:** A 12-column grid is centered within the `container-max` (1180px). 
- **Rhythm:** A strict 4px/8px incremental system.
- **Sectioning:** Vertical separation between major themes is aggressive (120px) to allow the "dark space" to act as a primary design element. 
- **Mobile Adaptivity:** At the 768px breakpoint, section padding reduces to 64px and page margins shrink to 24px. The grid collapses to a single column for project cards while maintaining the 3D tilt interaction (if touch-supported).

## Elevation & Depth

Elevation is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional drop shadows.

1.  **Background (Level 0):** Pure `#0a0c10`.
2.  **Surface (Level 1):** `#161b22` with a `1px` border of `border-glass`. This is the standard for cards.
3.  **Overlay (Level 2):** Fixed navigation and modals. Uses a 70% opacity background with a `14px` backdrop-blur. 
4.  **Active Focus:** When an element is hovered or active, it gains a subtle interior glow or an "outer-glow" using the primary amber at 10-15% opacity.

The "3D Tilt" interaction on project cards provides the final layer of depth, physically shifting the card in Z-space rather than relying on shadow cues alone.

## Shapes

The shape language is **Refined-Soft**. While the overall aesthetic is technical, the use of rounded corners (0.5rem base) prevents the UI from appearing too aggressive or dated.

- **Container Radius:** Cards and primary panels use `rounded-lg` (1rem).
- **Interactive Radius:** Buttons and input fields use `9px` to provide a distinct look from larger cards.
- **Metadata Shapes:** Tags and small indicators use a hybrid approach: technical data tags use the base `7px` radius, while "status" indicators use a full Pill shape (100px).

## Components

### Buttons & Inputs
- **Primary Button:** Solid `#c17d2e` background with `#0a0c10` (dark) text. On hover, apply a `box-shadow` glow.
- **Ghost Button:** `1px` solid `border-glass`. Background fills to 10% white on hover.
- **Input Fields:** Darker than the card surface (`#0a0c10`), using a thin bottom-border that glows amber on focus.

### Cards
- **Project Cards:** Feature a `1px` border. The background should be a subtle gradient from the top-left to bottom-right to simulate a light hitting a technical surface.
- **3D Effect:** Apply `transform-style: preserve-3d` to the card container.

### Chips & Tags
- **Skill Tags:** Use the `eyebrow-mono` type style. Background is a dark tint of indigo (`#55609e` at 15%) with a border of the same color at 30%.

### Lists & Timelines
- **Timeline Track:** A `2px` solid line using `border-glass`. The "active" nodes should use the primary amber glow to signify current status or highlights.

### Glass Navigation
- **Header:** Sticky position, 70% opacity of the background color with a blur. Use a single `1px` solid line at the bottom for separation.