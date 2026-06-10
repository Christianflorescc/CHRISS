---
name: Melancholic Minimalism
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0d0e0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#080808'
  on-primary-container: '#7a7878'
  inverse-primary: '#5f5e5e'
  secondary: '#c8c6c7'
  on-secondary: '#303031'
  secondary-container: '#49494a'
  on-secondary-container: '#bab8b9'
  tertiary: '#c8c6c8'
  on-tertiary: '#303032'
  tertiary-container: '#08080a'
  on-tertiary-container: '#79787a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e5e2e3'
  secondary-fixed-dim: '#c8c6c7'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474647'
  tertiary-fixed: '#e4e2e4'
  tertiary-fixed-dim: '#c8c6c8'
  on-tertiary-fixed: '#1b1b1d'
  on-tertiary-fixed-variant: '#474649'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '300'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1140px
  gutter: 32px
  margin-edge: 64px
  section-gap: 128px
---

## Brand & Style

The design system is built on the concept of "Physical and Emotional Distance." It evokes a sense of introspection, quietude, and the somber beauty of solitude. The aesthetic is heavily influenced by **Minimalism** with a touch of **Modern Editorial** design, prioritizing significant whitespace to represent the literal gaps between people.

The mood is quiet and respectful, utilizing a "black rain" atmosphere—dark, textured, and immersive. Visual elements are stripped to their essentials, ensuring that every piece of content feels intentional and carries weight. There is no room for decorative fluff; the beauty comes from the void and the stark contrast between light and shadow.

## Colors

The palette is a monochromatic exploration of darkness. 

- **Primary (#080808):** A deep, "obsidian" black used for the main canvas, representing the depth of the theme.
- **Secondary (#1A1A1B):** A muted charcoal for surface containers and section separation.
- **Tertiary (#2C2C2E):** A lighter slate for borders and subtle UI elements.
- **Accent/Neutral (#E2E2E2):** A soft, pale gray—rather than a harsh pure white—to ensure legibility while maintaining the somber, low-light atmosphere.

Color usage should be sparse. High contrast is reserved strictly for text and primary actions to guide the user through the gloom.

## Typography

Typography is the primary vehicle for emotion in this design system. 

- **Headlines:** We use **Playfair Display**. Its high-contrast serifs and elegant curves provide a literary, reflective quality. Use large sizes with tight letter-spacing for a cinematic effect.
- **Body:** We use **Inter**. Its systematic and neutral nature acts as a grounded counter-balance to the emotional serif. Light weights (300) are preferred to maintain a delicate, airy feel amidst the dark background.
- **Labels:** Small, uppercase Inter labels with generous letter-spacing should be used for navigation and metadata, mimicking the feel of a museum plaque or an architectural blueprint.

## Layout & Spacing

The layout philosophy is based on **isolation.** We use a **Fixed Grid** system that feels rigid and deliberate, but with unusually large margins and gaps to emphasize the distance between content blocks.

- **Desktop:** A centered 12-column grid with wide 64px outer margins.
- **Negative Space:** Sections should be separated by significant vertical gaps (128px+) to allow the user's eyes to rest and reflect. 
- **Alignment:** Content should often be asymmetrical or pushed to the edges of the grid to create a sense of tension and "stretching" between elements.
- **Mobile:** Transition to a single-column stack with 24px side margins, maintaining the vertical breathing room between components.

## Elevation & Depth

This design system avoids shadows entirely to maintain a flat, grounded, and "heavy" aesthetic. Depth is achieved through **Tonal Layering** and **Low-Contrast Outlines.**

- **Tiers:** The background is the darkest layer (#080808). Secondary information or cards sit on a slightly lighter surface (#1A1A1B).
- **Hairline Borders:** Use thin, 1px borders in the tertiary color (#2C2C2E) to define shapes without adding visual bulk.
- **Opacity:** Use varying levels of opacity (e.g., 60% white for secondary text) to create a sense of atmospheric perspective, as if some elements are receding into the "rain."

## Shapes

The shape language is strictly **Rectangular (0px radius).** 

Sharp corners convey a sense of precision, rigidity, and perhaps a touch of harshness that aligns with the theme of distancing. All containers, buttons, inputs, and image frames must adhere to this rule. Avoid circles or rounded elements; even avatars should be presented as sharp squares.

## Components

### Buttons
Buttons are strictly rectangular.
- **Primary:** Pale gray background (#E2E2E2) with black text. High contrast to signify a point of contact.
- **Secondary:** Ghost style. 1px border (#2C2C2E) with soft white text. No background.
- **Hover State:** Subtle increase in border brightness or a very slight shift in background tone. No rapid movements or "bouncy" animations.

### Input Fields
Inputs are simple 1px bottom-borders or full rectangles with no fill. Focus states are indicated by the border turning from muted charcoal to the soft white accent.

### Cards
Cards are used to house "moments" or "thoughts." They should have a background of #1A1A1B and no shadow. Use generous internal padding (min 32px) to ensure the content within doesn't feel crowded.

### Lists
Lists should be separated by thin, full-width dividers. Each item should have significant vertical padding (24px - 32px) to visualize the distance between entries.

### Media & Imagery
Images should be desaturated or treated with a dark overlay to match the "black rain" aesthetic. All images must be sharp-edged. Consider using wide-aspect ratios (21:9) to enhance the cinematic feel.