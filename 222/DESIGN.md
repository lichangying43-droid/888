---
name: Modern Culinary Heritage
colors:
  surface: '#faf9fd'
  surface-dim: '#dbd9dd'
  surface-bright: '#faf9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f7'
  surface-container: '#efedf1'
  surface-container-high: '#e9e7eb'
  surface-container-highest: '#e3e2e6'
  on-surface: '#1a1b1e'
  on-surface-variant: '#434843'
  inverse-surface: '#2f3033'
  inverse-on-surface: '#f1f0f4'
  outline: '#737873'
  outline-variant: '#c3c8c1'
  surface-tint: '#4f6355'
  primary: '#172a1e'
  on-primary: '#ffffff'
  primary-container: '#2d4033'
  on-primary-container: '#96ab9b'
  inverse-primary: '#b6ccba'
  secondary: '#78583e'
  on-secondary: '#ffffff'
  secondary-container: '#fdd2b1'
  on-secondary-container: '#78583f'
  tertiary: '#262622'
  on-tertiary: '#ffffff'
  tertiary-container: '#3c3c37'
  on-tertiary-container: '#a7a69f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e8d6'
  primary-fixed-dim: '#b6ccba'
  on-primary-fixed: '#0d1f14'
  on-primary-fixed-variant: '#384b3e'
  secondary-fixed: '#ffdcc2'
  secondary-fixed-dim: '#e8be9f'
  on-secondary-fixed: '#2c1603'
  on-secondary-fixed-variant: '#5d4128'
  tertiary-fixed: '#e4e2db'
  tertiary-fixed-dim: '#c8c7bf'
  on-tertiary-fixed: '#1b1c17'
  on-tertiary-fixed-variant: '#474741'
  background: '#faf9fd'
  on-background: '#1a1b1e'
  surface-variant: '#e3e2e6'
typography:
  display-lg:
    fontFamily: notoSerif
    fontSize: 56px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: notoSerif
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: notoSerif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: plusJakartaSans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin: 48px
  container-max-width: 1200px
---

## Brand & Style

This design system is built to evoke the atmosphere of a refined yet welcoming dining room. It balances the precision of modern gastronomy with the warmth of organic hospitality. The brand personality is "The Sophisticated Host"—attentive, knowledgeable, and grounded in tradition but expressed through contemporary aesthetics.

The design style leans into **Minimalism** with **Tactile** influences. It utilizes generous white space (or rather, "cream space") to allow photography to breathe, paired with subtle textures and a layout that feels curated rather than crowded. The visual language avoids the coldness of corporate tech by prioritizing organic tones and high-quality typography, ensuring the digital experience feels as bespoke as a hand-printed menu.

## Colors

The palette is rooted in an "Earthy Sophistication" theme. It moves away from high-contrast blacks and whites toward a more natural, muted spectrum:

*   **Primary (Deep Forest Green):** Used for key branding elements, primary actions, and deep backgrounds. It provides a sense of growth and stability.
*   **Secondary (Warm Walnut):** A rich wood-inspired brown used for accents, secondary buttons, and decorative elements that require a sense of "handcrafted" warmth.
*   **Tertiary (Cream):** This replaces pure white as the primary surface color. It reduces eye strain and provides a softer, more premium feel reminiscent of heavy-weight paper or linen.
*   **Neutral (Charcoal):** A softened black used for body text and structural borders to ensure high readability without the harshness of #000000.

The design should predominantly use the Cream (#F2F0E8) for large surfaces, with the Forest Green providing the weight for headlines and call-to-actions.

## Typography

The typography strategy employs a classic "Serif for Soul, Sans for Service" approach. 

**Noto Serif** is used for all headlines and display text. Its timeless proportions and elegant terminals convey authority and heritage. Use it for menu category headers, restaurant names, and philosophical pull-quotes.

**Plus Jakarta Sans** provides the modern counter-balance. Its clean, open apertures make it highly legible for ingredient lists, reservation details, and contact information. 

Large display type should be set with slightly tighter letter spacing to feel like editorial typesetting, while labels used for navigation or price points should use a slight letter-spacing increase and uppercase styling to provide a clear functional hierarchy.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain an editorial, magazine-like feel. Content is centered within a 1200px container to ensure that high-resolution food photography remains impactful and focused.

The spacing rhythm is based on a 4px baseline, but the system prioritizes "macro-spacing"—using large margins (48px+) between sections to create a feeling of luxury and calm. 

*   **Hero Sections:** Use full-bleed imagery with centered typography overlay.
*   **Menu Layouts:** A 2-column asymmetric grid where one side may contain imagery and the other contains text, mimicking a physical menu folder.
*   **Interactive Elements:** Use generous padding (16px–24px) within buttons and cards to reflect the "breathing room" found in high-end dining environments.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Ambient Shadows** rather than aggressive elevation. 

1.  **Base Layer:** The Cream (#F2F0E8) background serves as the foundation.
2.  **Surface Tier:** Cards and containers use #FFFFFF (Pure White) or a very subtle 1px border in the Secondary Wood Brown at low opacity (15%).
3.  **Shadows:** When used, shadows must be extremely soft, utilizing the Forest Green or Wood Brown as the shadow tint rather than gray. This creates a "warm" glow that feels like natural lighting in a restaurant.

Floating elements like "Book a Table" buttons should appear as if they are resting on a surface, using a low-blur, medium-spread shadow to feel tactile and physical.

## Shapes

The shape language is **Soft (0.25rem)**. 

Sharp edges (0px) are too clinical and aggressive for a hospitality brand, while overly rounded or pill-shaped buttons feel too "techy" and casual. The 0.25rem (4px) corner radius provides a subtle softening that makes the UI feel approachable while maintaining the structural integrity and sophistication of a high-end brand. 

Images of food or interiors should occasionally use larger radii (rounded-lg or rounded-xl) or even organic, non-uniform shapes to break the rigidity of the grid and emphasize the natural origins of the ingredients.

## Components

### Buttons
*   **Primary:** Forest Green background with Cream text. Soft corners. High-end buttons should include a subtle transition to Wood Brown on hover.
*   **Secondary:** Wood Brown border (1px) with Forest Green text. No fill.

### Cards
*   Used for "Featured Dishes" or "Events." Cards should have no shadow by default, instead using a 1px Cream-to-Charcoal border. On hover, apply a soft, warm-tinted shadow.

### Input Fields & Selectors
*   Minimalist design. Only a bottom border (1px) in Charcoal, which thickens to 2px in Forest Green when focused. This mimics the elegant look of a guest check or ledger.

### Chips
*   Used for dietary labels (e.g., "Vegan," "Gluten-Free"). Use small, uppercase labels with a Forest Green outline and a Cream background.

### Special Components
*   **The Signature Menu Item:** A specialized list item component that features the Noto Serif font for the dish name, a thin dotted "leader" line connecting to the price, and a Plus Jakarta Sans description below.
*   **Reservation Bar:** A sticky bottom component or top-header integration that remains accessible without obstructing the visual storytelling of the photography.