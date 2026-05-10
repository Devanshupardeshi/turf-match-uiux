---
name: Athletic Premium India Edition
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#32394c'
  surface-container-lowest: '#070e1e'
  surface-container-low: '#141b2c'
  surface-container: '#181f31'
  surface-container-high: '#232a3c'
  surface-container-highest: '#2e3447'
  on-surface: '#dce2fa'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dce2fa'
  inverse-on-surface: '#293042'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#71a1ff'
  on-tertiary-container: '#00367a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#0c1324'
  on-background: '#dce2fa'
  surface-variant: '#2e3447'
typography:
  display-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 32px
  title-md:
    fontFamily: Lexend
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
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
  xs: 0.25rem
  sm: 0.5rem
  md: 1rem
  lg: 1.5rem
  xl: 2.5rem
  container-margin: 1rem
  gutter: 1rem
---

## Brand & Style

The design system is engineered for the high-intensity world of Indian cricket. It balances the raw, kinetic energy of a stadium under floodlights with the sophisticated, "premium-performance" aesthetic of global athletic brands. The target audience is the digitally native Indian cricket enthusiast who expects the speed of a delivery-first app (Zomato/Blinkit) but desires the cultural resonance of local heritage.

The style is **High-Contrast / Bold**, utilizing deep shadows and vibrant accents to create a sense of urgency and motion. We integrate traditional Indian motifs—specifically geometric textile patterns and subtle mandala line-work—as functional background textures to ground the modern UI in a localized context. The emotional response should be one of "Match Day" excitement: fast, elite, and deeply connected to the game.

## Colors

The palette is anchored by "Deep Slate," providing a high-contrast foundation that makes the accent colors vibrate. 

- **Emerald Green (#10b981):** Represents the "Pitch" and positive action (success, booking, active status).
- **Saffron (#f59e0b):** Used for highlights, premium features, and high-energy alerts (live scores, "Man of the Match").
- **Surface Tiers:** We use incremental shifts in slate brightness to create hierarchy, ensuring the background never feels flat. 
- **UPI Integration:** For payment flows, use brand-accurate colors for GPay (Blue/Green/Yellow/Red) and Paytm (Light Blue) to instill immediate trust and recognition during checkout.

## Typography

This design system uses a dual-font strategy to balance impact with readability. 

- **Display & Headlines:** Anton is used for primary headers and scoreboards. Its condensed, heavy nature mimics sports broadcasting graphics. Always use uppercase for display levels to maximize the "Athletic Premium" vibe.
- **Body & Technical Info:** Lexend is utilized for all functional text, player stats (Batsman/Bowler/All-Rounder), and UI labels. Its geometric clarity ensures legibility during fast scrolling.
- **Localization:** Ensure line heights are generous enough to accommodate Hindi script or other regional languages if localized content is served.

## Layout & Spacing

The system follows a **Fluid Grid** model with an 8px base rhythm. 

- **Mobile First:** Standard 4-column grid for mobile with 16px side margins. 
- **Stacking:** Use "tight" spacing (4px-8px) for related data points like "Overs" and "Runs," and "wide" spacing (24px+) to separate distinct sections like "Upcoming Matches" and "Community Feed."
- **Visual Pace:** To emulate the speed of Blinkit/Zomato, use horizontal scrolling carousels for player cards and match highlights to keep the vertical scroll focused and fast.

## Elevation & Depth

Depth is communicated through **Tonal Layers** and **Ambient Shadows**, avoiding heavy skeuomorphism in favor of a "Glow" effect.

- **Primary Elevation:** Elements like "Book Now" buttons or Live Score cards use a subtle Emerald Green outer glow (0px 4px 20px rgba(16, 185, 129, 0.3)) instead of a traditional black shadow.
- **Layering:** Background uses #0c1324. Surface cards use #161f33. Floating Action Buttons (FABs) use #1e293b with a 1px border of #ffffff10 to catch the light.
- **Pattern Overlay:** Apply a 5% opacity Mandala or geometric textile pattern to the main background. This should be fixed, allowing content cards to slide over the "texture" of the app.

## Shapes

The shape language is **Rounded** to maintain a modern, app-centric feel while appearing approachable.

- **Standard Elements:** Cards, input fields, and "Pitch" maps use a 0.5rem (8px) radius.
- **Action Elements:** Buttons and UPI "Quick Pay" chips use a Pill-shape (full round) to distinguish them as interactive, high-priority touchpoints.
- **Textile Motifs:** Geometric patterns should utilize sharp 45-degree angles to contrast against the rounded UI elements, creating a "Modern-Traditional" tension.

## Components

- **Action Buttons:** Primary buttons are Emerald Green with Anton (Uppercase) text. Use a "speed-slant" (slight italicization or skew) for secondary action buttons to imply motion.
- **Live Score Cards:** Use Saffron for the "LIVE" indicator with a pulsing animation. Localized terminology is mandatory: "Wickets," "Overs," "Batsman," and "Bowler" labels must be prominent.
- **UPI Payment Module:** Direct integration of Paytm/GPay icons within the checkout flow. Use high-visibility Saffron for the "Confirm Payment" button.
- **Player Chips:** All-Rounders, Bowlers, and Batsmen are identified by color-coded chips with small geometric icons (Bat, Ball, or Both).
- **Pitch Selector:** A custom component representing the cricket pitch, using Emerald Green gradients to show "Hard," "Dusty," or "Green" pitch conditions.
- **Textile Borders:** Use thin (1px) Saffron or Green geometric patterns as separators between major sections instead of flat lines.