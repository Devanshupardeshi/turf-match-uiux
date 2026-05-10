---
name: TurfMatch Design System
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
  secondary: '#586062'
  on-secondary: '#ffffff'
  secondary-container: '#dae1e3'
  on-secondary-container: '#5d6466'
  tertiary: '#5c5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#9ea1a1'
  on-tertiary-container: '#343838'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7afd86'
  primary-fixed-dim: '#5ce06d'
  on-primary-fixed: '#002106'
  on-primary-fixed-variant: '#005319'
  secondary-fixed: '#dde4e6'
  secondary-fixed-dim: '#c1c8ca'
  on-secondary-fixed: '#161d1f'
  on-secondary-fixed-variant: '#41484a'
  tertiary-fixed: '#e1e3e3'
  tertiary-fixed-dim: '#c4c7c7'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#444748'
  background: '#f4fcee'
  on-background: '#161d15'
  surface-variant: '#dde5d8'
typography:
  headline-xl:
    fontFamily: Lexend
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Lexend
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 16px
  gutter: 12px
  stack-sm: 4px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

This design system is built on the philosophy of **High-Performance Athleticism**. It bridges the gap between the raw energy of recreational street cricket and the organized precision of professional sports technology. The visual direction is **Modern Minimalism**, emphasizing speed, clarity, and community action.

The system targets local players and organizers in India who need to make quick decisions—finding a game, booking a turf, or checking a score—in fast-paced, often bright outdoor environments. The interface uses heavy whitespace to offset vibrant brand colors, ensuring the app remains functional and "cool" under high-pressure usage.

## Colors

The color palette is derived from the tactile elements of the game. 

- **Turf Green (Primary):** A high-visibility, vibrant green used exclusively for primary actions, success states, and key brand highlights. It represents the field of play.
- **Slate Grey (Secondary):** Used for primary text and structural elements like the bottom navigation bar. It provides a grounded, professional contrast to the green.
- **Cricket White (Backgrounds):** A crisp, slightly cool white used for the main application background and card surfaces to ensure maximum readability in daylight.
- **Leather Red (Accent):** Reserved for "Live" match indicators, critical alerts, and high-energy status updates.
- **Wicket Wood (Subtle Accent):** A neutral brown used for secondary metadata or iconography to add a grounded, organic touch.

## Typography

The design system utilizes **Lexend**, a typeface specifically designed to reduce visual noise and improve reading performance. Its geometric, open terminals provide an "athletic" feel without sacrificing the cleanliness required for a modern tech product.

The type scale is optimized for mobile-first consumption:
- **Headlines:** Bold and tight-tracking to mimic the impact of sports headlines.
- **Body:** Generous line-height to ensure legibility when users are on the move.
- **Labels:** Used for metadata (e.g., match time, player count) with slight tracking increases for clarity at small sizes.

## Layout & Spacing

This design system follows a strict **8px soft-grid system** to maintain a rhythmic, organized feel. 

- **Mobile Philosophy:** A fluid grid with 16px side margins. Elements are stacked vertically to prioritize thumb-reach and one-handed operation.
- **Rhythm:** Use `stack-md` (16px) for spacing between unrelated components and `stack-sm` (4px) for grouping related text elements (e.g., a headline and its caption).
- **Safe Areas:** Bottom navigation and floating action buttons (FABs) must account for mobile OS safe areas to prevent interference with system gestures.

## Elevation & Depth

To maintain a minimalist aesthetic while ensuring hierarchy, the system uses **Ambient Shadows**. 

Depth is communicated through three tiers:
1. **Base (0dp):** The main background (Cricket White).
2. **Surface (2dp):** Cards and match listings. These use a very soft, diffused shadow (Blur: 12px, Y: 4px, Opacity: 6% Black) to "float" slightly above the background without looking heavy.
3. **Overlay (8dp):** Bottom navigation and Modals. These use a more pronounced shadow to indicate they are temporary or persistent global controllers.

Layering is preferred over heavy borders to keep the UI feeling "light" and high-performance.

## Shapes

The shape language is consistently **Rounded (Level 2)**. This specific curvature (8px base) balances the friendliness of a community app with the structural integrity of a sports utility.

- **Standard Elements (8px):** Primary buttons, input fields, and match cards.
- **Large Elements (16px - 24px):** Profile sections and map-view containers.
- **Pills:** Used exclusively for status chips (e.g., "Open to Players" or "Live") and the active state in the bottom navigation.

## Components

### Buttons
- **Primary:** Solid "Turf Green" with white text. High-contrast, rounded-md corners.
- **Secondary:** Transparent with a 1px "Slate Grey" border. Used for "Cancel" or "View History."
- **FAB:** A circular Turf Green button for "Create Match," typically located at the bottom right.

### Match Cards
- Background: White.
- Shadow: Soft ambient shadow.
- Structure: Left-aligned title, sub-text for location with a small map pin icon, and a "Join" button pinned to the bottom right or centered at the bottom.

### Bottom Navigation
- Background: "Slate Grey" or White with a top border.
- Active State: The active icon should be "Turf Green" or contained within a subtle green pill background.
- Labels: Always visible for core accessibility.

### Map-Inspired Elements
- Use "Map Pin" iconography that incorporates the Turf Green color. 
- Location-based filters should appear as horizontal scrolling chips (Pill-shaped) at the top of the feed.

### Inputs
- Clean, 1px bordered boxes that turn "Turf Green" when focused. Labels should be small and positioned above the field to maximize vertical space.