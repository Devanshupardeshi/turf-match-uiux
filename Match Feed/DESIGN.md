---
name: Cricket Quick-Commerce
colors:
  surface: '#f4fcee'
  surface-dim: '#d4dccf'
  surface-bright: '#f4fcee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef6e9'
  surface-container: '#e8f0e3'
  surface-container-high: '#e3ebdd'
  surface-container-highest: '#dde5d8'
  on-surface: '#161d15'
  on-surface-variant: '#3e4a3c'
  inverse-surface: '#2b322a'
  inverse-on-surface: '#ebf3e6'
  outline: '#6d7b6a'
  outline-variant: '#bdcab8'
  surface-tint: '#006e23'
  primary: '#006e23'
  on-primary: '#ffffff'
  primary-container: '#2eb84b'
  on-primary-container: '#004112'
  inverse-primary: '#5ce06d'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#505f76'
  on-tertiary: '#ffffff'
  tertiary-container: '#92a2ba'
  on-tertiary-container: '#29384d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7afd86'
  primary-fixed-dim: '#5ce06d'
  on-primary-fixed: '#002106'
  on-primary-fixed-variant: '#005319'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f4fcee'
  on-background: '#161d15'
  surface-variant: '#dde5d8'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
  body-sm:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-bold:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Lexend
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 10px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  margin-mobile: 12px
  gutter: 8px
---

## Brand & Style

This design system is engineered for a high-velocity, high-information cricket experience. It draws direct inspiration from the "Quick-Commerce" (Q-Commerce) sector—specifically delivery apps—prioritizing speed of consumption, dense data visualization, and an energetic, "now" feel.

The style is **High-Contrast Modernism**. It eschews soft shadows and gradients for sharp outlines, vibrant primary strikes, and a hyper-efficient layout model. The personality is active, clear, and motivating, aiming to evoke the same urgency one feels during a "Filling Fast" ticket sale or a live "Final Over."

Key visual pillars:
- **Efficiency over White Space:** Density is a feature, not a bug. Information is packed tightly to allow users to scan scores, players, and odds without excessive scrolling.
- **Urgency Signals:** Constant use of micro-copy and badges to communicate live status.
- **Functional Sharpness:** A preference for 1px strokes and precise geometry over soft organic shapes.

## Colors

The palette is designed for maximum legibility and brand recognition. 

- **Primary (Neon Green):** Reserved for primary calls to action, live status indicators, and branding moments. It must remain vibrant against the off-white surface.
- **Surface (Light Mint):** A cool, refreshing off-white used for the global background to reduce eye strain while maintaining a high-energy feel.
- **Typography & Accents (Sharp Black):** Used for all primary text and critical UI boundaries to provide a grounded, high-contrast anchor for the neon green.
- **Borders (Slate Gray):** A subtle #e2e8f0 or similar slate is used for secondary containers to keep the UI from feeling "heavy" while maintaining structure.

## Typography

This design system utilizes **Lexend** for its inherent athletic readability and modern geometric construction. 

The typographic scale is characterized by:
- **Tight Verticality:** Line heights are kept close to the font size (often 100-110%) to enable the high-density layout.
- **Aggressive Weight:** Headings should be bold or extra-bold to create clear hierarchy against dense data sets.
- **Negative Kerning:** Display styles use negative letter spacing to feel "packed" and impactful, mirroring tabloid sports headlines or fast-moving ticker tapes.

## Layout & Spacing

The layout philosophy is a **Dense Fluid Grid** optimized for mobile-first consumption. 

- **Grid:** A 4-column grid for mobile with very tight 8px gutters. 
- **Margins:** Standard outer margins are set to 12px to maximize horizontal real estate.
- **Information Density:** Components should use `8px` (sm) or `12px` (md) internal padding. Large gaps are discouraged. 
- **Rhythm:** A strict 4px baseline grid ensures alignment across multi-column data points (e.g., player stats, scorecards).

## Elevation & Depth

This design system rejects traditional shadows in favor of **Layered Outlines**. 

- **Flat Architecture:** Depth is communicated through color blocks and 1px borders rather than Z-axis elevation. 
- **The 1px Rule:** All cards and containers use a 1px solid border (#e2e8f0). 
- **Active State Elevation:** Only when an element is "pressed" or "active" does it receive a slight tonal shift (e.g., a primary green tint) rather than a shadow.
- **Sticky Elements:** The bottom navigation and top headers use a subtle blur effect (`backdrop-filter: blur(10px)`) over the Mint surface to maintain context while scrolling.

## Shapes

The shape language is "Soft-Sharp." 

- **Base Radius:** A standard 8px radius for all cards and primary buttons. This provides just enough softness to feel modern without losing the "utility" feel of the 1px outline.
- **Micro-Elements:** Badges and tags use a smaller 4px radius or a full pill shape for high-contrast "Live" status indicators.
- **Icons:** Icons should be framed in square or slightly rounded (4px) containers to match the density of the grid.

## Components

### Buttons & Actions
- **Primary Button:** Solid #2eb84b with black text or white text depending on contrast checks. 8px radius, bold Lexend.
- **Secondary Button:** White surface with 1px black outline.
- **Ghost Action:** Bold Lexend text with a right-chevron, no container.

### Cards & Slots
- **Data Cards:** 1px border (#e2e8f0), 8px radius, no shadow. Content is divided by subtle 1px horizontal dividers.
- **Player/Ground Slots:** Use high-quality photography with a dark gradient overlay at the bottom for white typography overlay.

### Badges & Urgency
- **Status Badges:** "LIVE", "FILLING FAST", "EXCLUSIVE". These use high-contrast backgrounds (Red for Live, Black for Urgency) and uppercase `label-bold` typography.
- **Micro-copy:** Small labels placed directly above headings to provide context (e.g., "MATCH 42 OF 70").

### Navigation
- **Bottom Bar:** High-density nav with 5 icons. Icons are bold/filled when active. No text labels if the icon is sufficiently clear, to save vertical space.
- **Segmented Control:** For switching between 'Squad', 'Live', and 'Stats'. Sharp 1px outlines with a black fill for the active state.

### Input Fields
- **Search/Filters:** Low-profile boxes with 1px slate borders. Focus state replaces slate with the Neon Green border.