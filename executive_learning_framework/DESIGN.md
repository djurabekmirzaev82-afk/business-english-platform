---
name: Executive Learning Framework
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#42474e'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#72777e'
  outline-variant: '#c2c7ce'
  surface-tint: '#396285'
  primary: '#00263f'
  on-primary: '#ffffff'
  primary-container: '#0b3c5d'
  on-primary-container: '#7fa7cd'
  inverse-primary: '#a3cbf2'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#361f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#533200'
  on-tertiary-container: '#e39100'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cee5ff'
  primary-fixed-dim: '#a3cbf2'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#1f4a6c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Poppins
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Poppins
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Poppins
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  title-lg:
    fontFamily: Poppins
    fontSize: 20px
    fontWeight: '500'
    lineHeight: '1.5'
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system is engineered for an elite corporate demographic, blending the structural authority of enterprise software with the fluidity of modern educational platforms. The brand personality is **Professional, Expert, and Empowering**. It seeks to evoke a sense of upward mobility and academic excellence through a high-fidelity aesthetic.

The chosen style is **Corporate Modern with Glassmorphism**. This approach utilizes a clean, whitespace-heavy foundation (Minimalism) to ensure focus on learning content, layered with frosted glass surfaces to provide a sense of depth and technical sophistication. The UI feels fast and responsive, utilizing subtle motion to guide the learner's journey without distraction.

## Colors

The palette is anchored by **Deep Navy (#0B3C5D)** to establish trust and institutional authority. **Emerald Green (#10B981)** is utilized for progression tracking, success states, and primary calls-to-action, signifying growth. **Gold (#F59E0B)** is reserved for premium features, achievements, and "Pro" tier highlights.

The color system supports both Light and Dark modes. In Dark mode, the background shifts to a deep midnight blue rather than pure black to maintain the premium, soft-contrast aesthetic. Glassmorphism effects must adjust their opacity and blur based on the active mode to ensure legible content layering.

## Typography

This design system employs a dual-font strategy. **Poppins** provides a contemporary, friendly, yet professional voice for all headings and display text. Its geometric nature complements the rounded UI elements. **Inter** is used for all body copy and UI labels, selected for its exceptional legibility and neutral tone, essential for dense educational content and assessment modules.

Hierarchical clarity is maintained through generous line heights (1.6 for body) to reduce cognitive load during long reading sessions.

## Layout & Spacing

The design system uses a **Fluid 12-column grid** for desktop and tablet, transitioning to a single-column layout for mobile. 

- **Desktop (1280px+):** 12 columns, 24px gutters, 64px page margins.
- **Tablet (768px - 1279px):** 8 columns, 16px gutters, 32px page margins.
- **Mobile (Up to 767px):** 4 columns, 16px gutters, 16px page margins.

Spacing follows a strict 4px base unit, with 16px (md) being the standard padding for most UI containers and 24px (lg) used for separating distinct sections of content.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **Glassmorphism** and **Ambient Shadows**. 

1.  **Base Layer:** The primary background color.
2.  **Mid Layer (Cards):** Slightly elevated using a very soft, diffused shadow (`0 4px 20px rgba(0,0,0,0.05)`) and a subtle 1px border (`rgba(255,255,255,0.1)`).
3.  **Top Layer (Modals/Navigation):** Utilizes a backdrop-blur effect (20px) with a semi-transparent surface. This "Glass" effect creates a sense of high-fidelity technology and maintains context of the layer beneath.

Shadows in Dark Mode should be darker and tighter, using the primary navy color as a tint (`rgba(5, 27, 42, 0.4)`) instead of pure black.

## Shapes

The shape language is defined by large, approachable radii that soften the corporate edge of the platform. Cards and major containers use a **2xl roundedness (1.5rem / 24px)**, creating a premium "app-like" feel. Interactive elements like buttons use a slightly smaller radius to maintain a sense of precision and clickability. Inputs follow a standard soft radius to ensure they remain professional and functional.

## Components

### Buttons
- **Primary:** Emerald Green background, white text. High-contrast, used for "Start Lesson" or "Subscribe."
- **Secondary:** Transparent with a 2px Primary Navy border. 
- **Ghost:** Subtle glass effect with a primary color text.

### Cards
- **Lesson Cards:** 24px border radius, subtle hover lift (translateY -4px), and a glassmorphic footer for progress indicators.
- **Course Cards:** Large imagery with a gradient overlay to ensure text legibility.

### Inputs
- **Text Fields:** White background (light mode) or deep navy (dark mode), 1px border. On focus, the border transitions to Primary Navy with a subtle 4px outer glow.

### Chips & Badges
- **Status Chips:** Small, pill-shaped, using low-opacity versions of the status color (e.g., Green for "Completed", Gold for "Pro").

### Progress Bars
- Smooth, animated transitions using Framer Motion logic. The bar should have a subtle inner glow to appear "liquid" and high-end.

### Navigation
- **Side Rail:** Fixed, glassmorphic rail for desktop.
- **Bottom Bar:** For mobile, utilizing a frosted glass background to allow content to scroll underneath beautifully.