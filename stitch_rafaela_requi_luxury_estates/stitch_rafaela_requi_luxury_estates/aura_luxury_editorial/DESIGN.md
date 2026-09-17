---
name: Aura Luxury Editorial
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fdd587'
  on-secondary-container: '#785a19'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1c'
  on-tertiary-container: '#828484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdea3'
  secondary-fixed-dim: '#e8c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5c4200'
  tertiary-fixed: '#e2e3e2'
  tertiary-fixed-dim: '#c6c7c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  gold-accent: '#c5a059'
  surface-muted: '#eeeeee'
  glass-overlay: rgba(25, 26, 26, 0.4)
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 24px
  editorial-step: 160px
---

## Brand & Style
The brand identity is centered on **high-end exclusivity, architectural precision, and editorial sophistication**. It targets ultra-high-net-worth individuals who value discretion, minimalist elegance, and a "white-glove" digital experience.

The design style is a blend of **Minimalism** and **Glassmorphism**. It utilizes expansive white space, high-contrast serif typography for storytelling, and delicate translucent layers to create a sense of depth without visual clutter. The emotional response should be one of serenity, aspiration, and absolute trust.

## Colors
The palette is rooted in a "Quiet Luxury" aesthetic. 
- **Primary (#1a1a1a):** A deep, near-black used for high-impact text and primary grounding elements.
- **Secondary (#775a19):** A sophisticated muted gold/bronze used sparingly for accents, highlights, and indicating premium status.
- **Neutral (#f9f9f9):** The foundational surface color, providing a clean, gallery-like backdrop.

Functional colors like "Error" should be used with extreme restraint to maintain the calm atmosphere. Transitions between light and dark modes should focus on preserving the high-contrast legibility of the serif display fonts.

## Typography
The typographic system relies on a sharp contrast between the **Bodoni Moda** (Display) and **Hanken Grotesk** (Functional). 

- **Headlines:** Use Bodoni Moda for all storytelling and section headers. Its high contrast and vertical stress evoke fashion and architectural magazines.
- **Body:** Hanken Grotesk provides a modern, clean, and highly legible experience for long-form descriptions.
- **Labels:** Upper-case Hanken Grotesk with generous letter spacing is used for eyebrows and metadata to create a "curated" feel.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy with a maximum container width of 1440px. The rhythm is intentionally sparse to allow high-resolution imagery to breathe.

- **Editorial Spacing:** Key sections are separated by a massive 160px vertical margin to signal a change in narrative.
- **Grid:** A 12-column system is used for the desktop layout, frequently employing asymmetrical offsets (e.g., a 5-column image next to a 6-column text block with a 1-column gap).
- **Responsive:** On mobile, the margins tighten to 24px, and all multi-column layouts stack vertically. Large headlines scale down significantly to maintain a maximum of 3-4 lines of text.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Ambient Shadows** rather than traditional stacking.

- **Navigation:** Uses a `backdrop-filter: blur(30px)` with a semi-transparent surface (80% opacity) to stay docked at the top without feeling heavy.
- **Shadows:** The "Soft Shadow" (`0 10px 40px -10px rgba(0,0,0,0.04)`) is used for cards and floating elements to provide a subtle lift that feels natural and airy.
- **Layering:** Editorial elements (like gold accent boxes) are often positioned "behind" images with negative Z-indices to create a sophisticated, layered depth similar to print layout design.

## Shapes
The shape language is **Sharp (0px)**. Rectilinear forms are essential to the architectural and high-fashion aesthetic.

- **Buttons & Cards:** These should have square corners (0px radius) to maintain a sense of formal discipline and precision.
- **Imagery:** Photos should remain sharp-edged. Any use of rounding should be reserved exclusively for "pill-shaped" tags (like status indicators) if a softer contrast is needed, though the default remains sharp.

## Components
- **Buttons:** Primary buttons are solid blocks (#1a1a1a) with white text in `label-caps`. Hover states transition to the secondary gold (#775a19). Secondary buttons are outlined or text-only with a subtle border.
- **Cards (Editorial):** Cards feature high-ratio images (16:9 or 4:3) with metadata positioned immediately below. Use thin `outline-variant/10` borders to define boundaries only when necessary.
- **Navigation:** The TopNavBar is a glass-morphic container. Menu items use `label-caps` and have subtle hover opacity changes.
- **Input Fields:** Underlined or minimally boxed with no border-radius. Focus states should use the secondary gold color.
- **Iconography:** Use Material Symbols Outlined with a weight of 300 or 400. Icons should be used sparingly as elegant accents rather than primary navigational elements.