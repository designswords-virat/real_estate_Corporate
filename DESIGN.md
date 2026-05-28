---
name: Architectural Prestige
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#44474c'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#525f71'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0f1c2c'
  on-primary-container: '#778598'
  inverse-primary: '#bac8dc'
  secondary: '#0058bd'
  on-secondary: '#ffffff'
  secondary-container: '#1470e8'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#101c29'
  on-tertiary-container: '#798595'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a41'
  on-secondary-fixed-variant: '#004494'
  tertiary-fixed: '#d7e4f5'
  tertiary-fixed-dim: '#bbc8d9'
  on-tertiary-fixed: '#101c29'
  on-tertiary-fixed-variant: '#3c4856'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 20px
  section-gap: 128px
---

## Brand & Style

The design system is engineered for high-end corporate real estate and architectural excellence. The brand personality is authoritative yet visionary, combining the structural integrity of a top-tier enterprise with the aesthetic finesse of a modern design studio. 

The visual direction follows a **Corporate Minimalist** aesthetic infused with **Glassmorphism** accents. It prioritizes clarity through generous whitespace, high-contrast typography, and a "less is more" philosophy. The emotional response should be one of absolute reliability, precision, and forward-thinking sophistication, mirroring the physical permanence of the structures the system represents.

## Colors

The palette is anchored by **Deep Navy** and **Graphite Black**, establishing a foundation of stability and professional gravity. **Corporate Blue** is used sparingly as a functional catalyst for actions and focus states, ensuring that the interface remains grounded. 

**Silver Accents** and **Steel Gray** provide the necessary gradients and borders to define space without introducing visual noise. The default background is **Soft White**, which provides a warmer, more premium feel than pure white, reducing eye strain and enhancing the "editorial" quality of the layout.

## Typography

This design system utilizes **Inter** for its systematic precision and exceptional legibility. The hierarchy is "Editorial-First," meaning large display sizes are used to create focus and narrative flow. 

Tight letter-spacing is applied to large headlines to maintain a compact, architectural feel. For body copy, line heights are slightly increased to ensure comfortable reading of technical specifications or project narratives. The `label-caps` style is used for eyebrows and metadata, providing a structured, categorized look to information blocks.

## Layout & Spacing

The design system employs a **Fixed Grid** model on desktop to maintain a controlled, high-end editorial feel. Layouts are based on a 12-column grid with generous 32px gutters to prevent content crowding.

Vertical rhythm is driven by a strict 8px baseline. Section gaps are intentionally large (128px on desktop) to allow the "architecture" of the UI to breathe. On mobile, the grid collapses to 4 columns with tighter margins, but the emphasis on whitespace remains to preserve the premium brand positioning. Content should reflow with a focus on verticality and large, full-bleed imagery.

## Elevation & Depth

Visual hierarchy is achieved through a mix of **Tonal Layering** and **Glassmorphism**. 

- **Surface Levels:** The primary background is Soft White. Secondary surfaces (cards, sidebars) use a subtle Silver Accent or pure White with a low-opacity Deep Navy border.
- **Glassmorphism:** Navigation bars and modal overlays utilize a frosted glass effect (backdrop-blur: 20px) with a 10% opacity white fill. This creates a sense of depth and modernity without feeling heavy.
- **Shadows:** Avoid heavy drop shadows. Use "Ambient Shadows"—extremely soft, large-radius blurs with very low opacity (3-5%) tinted with Deep Navy to make elevated elements feel as though they are floating naturally in space.

## Shapes

The shape language is **Soft (0.25rem)**. This choice strikes a balance between the rigid, sharp lines of traditional corporate architecture and the approachable, modern feel of contemporary digital products. Buttons, input fields, and containers use consistent 4px radii. Large images and main cards may scale up to 8px or 12px radii to feel more intentional, but excessive roundness is avoided to maintain a professional edge.

## Components

- **Buttons:** Primary buttons are solid Deep Navy with white text. Secondary buttons use a ghost style with a 1px Steel Gray border. Hover states should include a subtle transition to Corporate Blue or a slight scale increase (1.02x) for a cinematic feel.
- **Input Fields:** Use a minimal underline or a 1px Silver Accent border. Labels should use the `label-caps` style above the field.
- **Cards:** Architectural project cards should be image-heavy with minimal metadata overlay. Use the glassmorphism effect for text containers that sit on top of images.
- **Progress Indicators:** Use thin, high-precision lines (1px or 2px) in Corporate Blue.
- **Navigation:** Top-level navigation is minimalist, utilizing the glassmorphic background on scroll to maintain context while keeping the architectural visuals visible beneath.
- **Interactive States:** All transitions (hover, focus, page entry) should be smooth, using a `cubic-bezier(0.2, 0, 0, 1)` easing for a professional, high-end motion feel.