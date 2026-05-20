---
name: Tactile High-Fidelity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#cfc2d5'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#988d9e'
  outline-variant: '#4c4353'
  surface-tint: '#deb7ff'
  primary: '#deb7ff'
  on-primary: '#4a007f'
  primary-container: '#9b51e0'
  on-primary-container: '#ffffff'
  inverse-primary: '#8135c5'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#f1bf54'
  on-tertiary: '#402d00'
  tertiary-container: '#997000'
  on-tertiary-container: '#080400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#deb7ff'
  on-primary-fixed: '#2c0050'
  on-primary-fixed-variant: '#670fac'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffdea2'
  tertiary-fixed-dim: '#f1bf54'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5c4200'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is centered on a premium, immersive audio experience that balances high-end technical precision with a tactile, physical interface. The brand personality is sophisticated and luxurious, targeting audiophiles who value both aesthetic craftsmanship and acoustic performance.

The visual direction utilizes a **Neumorphic (Soft UI)** approach, where the interface appears to be sculpted from a single slab of charcoal material. By using dual-tone shadows to simulate light displacement, the UI moves away from flat digital trends toward a more "equipment-inspired" feel, mimicking the physical buttons and casing of professional audio gear. The atmosphere is dark and focused, allowing the "Premium Purple" accent to serve as a high-energy indicator of power and connectivity.

## Colors
The palette is dominated by **Dark Charcoal (#121212)**, which serves as the physical "material" of the interface. 

*   **Primary (Premium Purple):** Used sparingly for interactive highlights, active states, and branding accents to signify energy.
*   **Neutral (White):** Reserved strictly for high-contrast legibility in text and iconography.
*   **Neumorphic Shadows:** To achieve the sculpted effect, the system uses two specific neutral derivatives. A "Light Highlight" (#1b1b1b) is applied to the top-left edges, and a "Deep Shadow" (#090909) is applied to the bottom-right edges of extruded elements.

## Typography
The design system exclusively uses **Montserrat** to maintain a clean, geometric, and modern architectural feel. 

Headlines use heavy weights and tight letter spacing to command attention, while body text maintains generous line height for readability against the dark background. A specialized "Label Caps" style is used for navigation and technical specifications to mimic the engraving found on premium hardware.

## Elevation & Depth
Elevation is not achieved through Z-index stacking but through **surface deformation**. 

*   **Extruded (Raised):** Default state for buttons and cards. Uses a background color of #121212 with a -5px -5px highlight (#1b1b1b) and a 5px 5px shadow (#090909).
*   **Inset (Sunken):** Used for active states and input fields. Uses internal shadows to create a "carved" look.
*   **Interactive Blur:** Large product imagery may use a soft background glow of the Primary Purple to create depth without using traditional drop shadows.

## Shapes
The shape language is consistently **Rounded (Level 2)**. 

The 0.5rem (8px) base radius is critical for the Neumorphic effect, as the dual-tone shadows require curved corners to wrap naturally and simulate a soft, molded plastic or matte metal surface. Large containers and hero cards should use `rounded-xl` (1.5rem) to further soften the high-tech aesthetic.

## Components

### Buttons
Buttons are the primary expression of the Neumorphic style.
*   **Standard:** Extruded surface with White text.
*   **Primary:** Subtle Purple border or Purple text highlight.
*   **Active/Pressed:** Transitions from extruded to inset (sunken) to provide physical feedback.

### Navigation Bar
A high-transparency or solid charcoal bar. Brand logo is positioned far-left, navigation links are center-aligned in "Label Caps" style with generous tracking, and utility icons (user, cart, menu) are grouped far-right.

### Cards & Hero Blocks
Product cards should appear to rise out of the background. Information is organized hierarchically with large font titles and small, high-contrast labels for technical attributes (e.g., "10 Drivers", "Ships in 1-4 Days").

### Input Fields
Inputs should always be "Inset" (sunken) to differentiate them from "Extruded" (clickable) elements. Use a thin 1px border of #1b1b1b to define the edge in low-light environments.