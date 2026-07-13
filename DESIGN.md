---
name: Academic Elegance
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#504444'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#827473'
  outline-variant: '#d4c2c2'
  surface-tint: '#7b5455'
  primary: '#7b5455'
  on-primary: '#ffffff'
  primary-container: '#f4c2c2'
  on-primary-container: '#734e4e'
  inverse-primary: '#ecbaba'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#5e5e5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#cfceca'
  on-tertiary-container: '#575855'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ecbaba'
  on-primary-fixed: '#2f1314'
  on-primary-fixed-variant: '#613d3e'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e2de'
  tertiary-fixed-dim: '#c8c6c3'
  on-tertiary-fixed: '#1b1c1a'
  on-tertiary-fixed-variant: '#474744'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
  italic-accent:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 28px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  margin-page: 2rem
  gutter-grid: 1.5rem
  section-gap: 4rem
  element-gap: 1rem
---

## Brand & Style
The design system embodies a "Commencement Couture" aesthetic, blending the prestige of academic achievement with the intimate, high-end feel of a premium wedding invitation. The target audience is a female university graduate seeking a digital space that feels like a physical keepsake—tactile, celebratory, and profoundly personal.

The style is a hybrid of **Minimalist Editorial** and **Tactile Luxury**. It leverages expansive whitespace to provide breathing room for decorative elements, ensuring the interface feels curated rather than cluttered. High-end paper textures, subtle letterpress effects, and gold foil accents create a sense of physical importance, while modern layout principles maintain digital usability. The emotional response should be one of "earned grace" and "sophisticated joy."

## Colors
The palette is rooted in soft, warm tones that evoke high-quality stationery.
- **Primary (Blush):** Used for soft backgrounds, accent shapes, and decorative watercolor washes. It provides the feminine, celebratory foundation.
- **Secondary (Champagne Gold):** Reserved for "special" moments—foil borders, icons, call-to-action highlights, and ornamental dividers.
- **Tertiary (Cream/Paper):** The primary background color. It is a warm, off-white that avoids the sterile feel of pure white, mimicking heavy cotton cardstock.
- **Neutral (Charcoal):** Used exclusively for typography and fine line-work to ensure high legibility and a classic "ink-on-paper" look.
- **Surface Accents:** Subtle hints of sage green or dusty rose may be used within floral illustrations to add depth without distracting from the core palette.

## Typography
The typography system relies on a high-contrast pairing to distinguish between "emotional" and "informational" content.
- **Headlines:** Use Playfair Display for all major headings, names, and celebratory callouts. Its high-contrast serifs evoke traditional invitation printing.
- **Body:** Source Sans 3 provides a clean, neutral balance, ensuring that long-form details like ceremony instructions or degree descriptions are effortless to read.
- **Labels:** Montserrat is used in uppercase with wide letter-spacing for small metadata, buttons, and navigation, providing a modern, organized contrast to the serif headings.
- **Styling Note:** Use the `italic-accent` role for pull-quotes, dates, or formal "You are cordially invited" style text to lean into the wedding-aesthetic narrative.

## Layout & Spacing
This design system utilizes a **Fixed Centered Grid** for desktop (12 columns, max-width 1140px) to mimic the structured layout of an invitation card. On mobile, it transitions to a fluid single-column layout with generous side margins (24px).

Spacing is intentionally "loose." Avoid packing elements tightly; instead, use `section-gap` to separate different phases of the experience (e.g., The Invite, The Schedule, The Gallery). Alignment should lean toward the center for a formal, traditional feel, though editorial sections may use asymmetrical layouts with large "white-space offsets" to create a premium feel.

## Elevation & Depth
Depth is achieved through **Tonal Layering** and **Subtle Textures** rather than heavy shadows.
- **The Base:** A soft, grain-textured cream surface.
- **Layering:** Use extremely thin (1px) gold foil borders or "blind emboss" effects (inner shadows with very low opacity) to define cards.
- **Shadows:** If used, shadows must be "Ambient Bloom"—low opacity (#D4AF37 at 10%), very large blur (30px+), and no offset, creating a soft glow rather than a lift.
- **Glassmorphism:** Use sparingly for overlay modals (e.g., "RSVP" forms), with a high background blur (20px) and a subtle blush-tinted opacity (80%).

## Shapes
The shape language is "Softly Architectural." 
- **Corners:** Standard UI elements use a subtle `0.25rem` radius to maintain a crisp, paper-like feel. 
- **Decorative Frames:** Use custom "Arch" or "Scalloped" shapes for photo containers and hero sections to mimic die-cut stationery.
- **Dividers:** Use horizontal lines with a gold foil gradient, often featuring a small floral ornament or a centered dot to break up sections.
- **Floral Masks:** Watercolor peonies should bleed off the edges of containers, breaking the rigid grid to add an organic, feminine touch.

## Components
- **Buttons:** Primary buttons are "Champagne Gold" with "Charcoal" text. They should have a subtle gold-to-light-gold linear gradient to mimic foil. Secondary buttons use a simple charcoal outline with high letter-spacing labels.
- **Cards:** Invitation cards should have a 1px gold border and a subtle paper texture background. They should never have hard shadows.
- **Inputs:** Form fields (like RSVP names) use only a bottom border (1px charcoal) to look like a handwritten fill-in-the-blank line on a physical card.
- **Chips/Tags:** Used for academic honors (e.g., "Cum Laude"). These should be styled as "Wax Seals"—circular or organic shapes in a deep rose or gold color.
- **Lists:** Use delicate floral bullet points or simple Roman numerals instead of standard dots.
- **RSVP Progress:** A thin, elegant line with small gold nodes to track the user's journey through the graduation events.