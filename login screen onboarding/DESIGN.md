---
name: Athletic Premium System
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#33394c'
  surface-container-lowest: '#070d1f'
  surface-container-low: '#151b2d'
  surface-container: '#191f31'
  surface-container-high: '#23293c'
  surface-container-highest: '#2e3447'
  on-surface: '#dce1fb'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dce1fb'
  inverse-on-surface: '#2a3043'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#45dfa4'
  on-secondary: '#003825'
  secondary-container: '#00bd85'
  on-secondary-container: '#00452e'
  tertiary: '#bec6e0'
  on-tertiary: '#283044'
  tertiary-container: '#9ba2bb'
  on-tertiary-container: '#31394d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#68fcbf'
  secondary-fixed-dim: '#45dfa4'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#0c1324'
  on-background: '#dce1fb'
  surface-variant: '#2e3447'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.0'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '900'
    lineHeight: '1.2'
  stat-lg:
    fontFamily: Anton
    fontSize: 56px
    fontWeight: '900'
    lineHeight: '1.0'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  micro-label:
    fontFamily: Lexend
    fontSize: 10px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.2em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '900'
    lineHeight: '1.1'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  container-padding: 1.5rem
  gutter: 1rem
  bento-gap: 1rem
  section-margin: 2.5rem
---

## Brand & Style

This design system is engineered for high-performance athletic environments, prioritizing immediate legibility and visceral energy. The brand personality is authoritative yet motivating, utilizing a high-contrast aesthetic that feels both premium and "hard-core." 

The design style is a hybrid of **High-Contrast Bold** and **Glassmorphism**. It leverages massive, aggressive typography to celebrate personal achievements and data, while using glassmorphic layers to maintain a sense of modern sophistication. The "Bento Box" layout ensures information is compartmentalized into digestible, modular units, reflecting the organized nature of professional training regimens.

## Colors

The palette is anchored in "Deep Slate" tones to provide a limitless sense of depth, ensuring the UI recedes so the user's data can pop. 

- **Primary & Secondary:** Emerald-500 and Emerald-400 serve as the "energy" colors. They are used exclusively for interactive elements, progress indicators, and critical success states.
- **Backgrounds:** Slate-950 is the base canvas. 
- **Surfaces:** Slate-900 is used for the Bento containers to create a subtle lift from the background.
- **Data Visualization:** Use the Emerald scale for positive trends, Slate-400 for neutral/secondary data, and a high-vibrancy Red-500 only for heart-rate warnings or missed goals.

## Typography

Typography is used as a primary graphical element. 

- **Headlines & Stats:** We use **Anton** for its condensed, powerful impact. It should be set in Black (900) weight. Large numbers (kilometers, pace, heart rate) must use Anton to evoke a "scoreboard" feel.
- **Body & Reading:** **Lexend** provides the necessary readability and athletic character for longer strings of text, specifically chosen for its focus on ocular speed.
- **Micro-labels:** Used for metadata above headings or within Bento cells. These must be uppercase with wide tracking (0.2em) to create a clear structural hierarchy against the heavy headlines.

## Layout & Spacing

The system uses a **Bento Box grid**—a modular, tile-based layout that scales across devices. 

- **Mobile:** A 2-column vertical stack. Most cards should span the full width (2 columns), with secondary stats occasionally splitting into a 50/50 side-by-side view.
- **Desktop/Tablet:** A 12-column grid where modules occupy units of 3, 4, or 6 columns. 
- **The Notch:** The top of the UI should simulate a hardware-notch integration, with "Status Bar" items (Time, Battery, Connectivity) hugging the notch geometry, creating a seamless hardware-to-software transition.
- **Safe Areas:** Maintain a 24px (1.5rem) margin around the perimeter of the screen to ensure content does not feel cramped.

## Elevation & Depth

Depth is achieved through layering and light, rather than traditional drop shadows.

- **Bento Containers:** These sit on the "Surface" level (Slate-900). They do not have shadows, but instead use a 1px inner border of `white/0.05` to catch the "light."
- **Emerald Glow:** Primary action buttons and active state cards utilize an "Emerald Shadow"—a diffused, colored glow (`rgba(16, 185, 129, 0.3)`) with a 20px blur to simulate a neon-underglow effect.
- **Floating Navigation:** The bottom tab bar is glassmorphic. It uses a `backdrop-filter: blur(20px)` with a `bg-slate-900/60` fill. It should appear to float 16px above the bottom edge of the screen.

## Shapes

The shape language is defined by **ultra-rounded corners**, creating a "friendly-tech" aesthetic that softens the aggressive typography.

- **Bento Tiles:** Use a consistent `2rem` (32px) corner radius. This is non-negotiable as it defines the "box" aesthetic.
- **Buttons:** Large buttons should be fully pill-shaped (rounded-full).
- **Inner Elements:** Small elements inside cards (like icon backgrounds) should use a nested radius of `1rem` to maintain visual harmony.

## Components

- **Buttons:** Primary buttons are Emerald-500 with Black Anton text. Secondary buttons are outlined in Emerald with no fill.
- **Bento Cards:** Every card is a Slate-900 container. Content within should be padded by 24px. Use "Micro-labels" at the top left of the card to categorize the data.
- **Input Fields:** Minimalist design with a Slate-800 background and a 2px Emerald bottom-border that illuminates when the field is focused.
- **Progress Rings:** Use thick strokes (min 8px) with rounded caps. The "Unfilled" portion should be Slate-800, and the "Filled" portion should be an Emerald-to-Teal gradient.
- **Floating Nav:** A detached, centered bar with high-contrast icons. The active icon should have a small Emerald dot indicator underneath it.
- **Data Visualization:** Line charts should use "Bezier" smoothing and an Emerald stroke, with a subtle Emerald-to-transparent vertical gradient fill beneath the line.