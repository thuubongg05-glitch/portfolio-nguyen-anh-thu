---
name: Luminous Editorial
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#504443'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#827473'
  outline-variant: '#d4c3c2'
  surface-tint: '#795555'
  primary: '#795555'
  on-primary: '#ffffff'
  primary-container: '#c89d9c'
  on-primary-container: '#533434'
  inverse-primary: '#e9bcba'
  secondary: '#645d5b'
  on-secondary: '#ffffff'
  secondary-container: '#ebe0de'
  on-secondary-container: '#6a6361'
  tertiary: '#5f5e5d'
  on-tertiary: '#ffffff'
  tertiary-container: '#a9a7a5'
  on-tertiary-container: '#3d3d3b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#e9bcba'
  on-primary-fixed: '#2e1414'
  on-primary-fixed-variant: '#5f3e3e'
  secondary-fixed: '#ebe0de'
  secondary-fixed-dim: '#cec4c3'
  on-secondary-fixed: '#1f1a1a'
  on-secondary-fixed-variant: '#4c4544'
  tertiary-fixed: '#e5e2e0'
  tertiary-fixed-dim: '#c8c6c4'
  on-tertiary-fixed: '#1b1c1b'
  on-tertiary-fixed-variant: '#474745'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Be Vietnam Pro
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
  margin-page: 3rem
  gutter-grid: 1.5rem
  stack-section: 4rem
  stack-element: 1rem
  padding-card: 1.5rem
---

## Brand & Style

The design system is an exercise in "Ethereal Minimalism," drawing direct inspiration from high-end skincare and editorial catalogs. It aims to elevate the standard CV from a functional document to a premium personal brand experience. The visual narrative is defined by:

- **Soft Luxury:** Utilizing a high-key color palette and generous negative space to create a sense of calm, breathing room, and prestige.
- **Editorial Precision:** A focus on high-contrast serif typography for headings to mimic the feeling of a boutique magazine or luxury skincare branding.
- **Organic Softness:** Subtle rounded corners and delicate accents replace harsh lines, evoking a sense of gentleness and approachability.
- **Refinement:** Intentional use of thin strokes and monochromatic textures to ensure the content remains the focal point while feeling "designed."

Targeting creative professionals, luxury sector applicants, and those in aesthetics-driven industries, this system prioritizes readability and emotional resonance.

## Colors

The palette is anchored in warm, skin-toned neutrals and sophisticated accents:

- **Primary (Dusty Rose - #C89D9C):** Reserved for high-impact elements like section headers, primary icons, and timeline markers. It provides warmth without aggressive contrast.
- **Secondary (Pale Pink - #FDF2F0):** Used for subtle container backgrounds, hover states, and tag fills.
- **Surface (Creamy White - #FCF9F7):** The canvas color. It is warmer than pure white, reducing eye strain and feeling more "premium."
- **Typography (Charcoal Black - #2D2D2D):** Provides the necessary legibility for long-form body text while appearing softer than true black.
- **Semantic Accents:** Use lowered opacities of the Primary color for success/info states to maintain the soft aesthetic.

## Typography

This system uses a classic pairing of a high-contrast serif and a modern humanist sans-serif.

- **Headings:** **Playfair Display** provides the luxury editorial feel. Section titles use the Primary color (#C89D9C) to create clear visual anchors.
- **Body & Metadata:** **Be Vietnam Pro** was chosen for its excellent Vietnamese language support and clean, approachable glyphs. It maintains legibility even at smaller sizes in dense CV sections.
- **Hierarchy:** Use uppercase and tracking (letter spacing) for labels and metadata (e.g., dates) to differentiate them from body text without needing to increase weight.

## Layout & Spacing

The layout philosophy is a **Fixed 12-Column Grid** for desktop and a **Single Column Fluid Grid** for mobile.

- **Desktop:** The content is centered with wide gutters. Sidebars (for contact info/skills) should occupy 4 columns, while main content (experience/education) occupies 8 columns.
- **Vertical Rhythm:** A "high-whitespace" approach is enforced. Sections are separated by large gaps (`stack-section`) to allow the eye to rest and emphasize the modularity of the career history.
- **Breathing Room:** Content should never feel cramped. Avoid using borders to separate sections; use whitespace and subtle background shifts (Surface vs Secondary color) instead.

## Elevation & Depth

This system avoids heavy shadows, favoring tonal layering and light-refraction metaphors:

- **Tonal Layers:** Cards sit on the Surface background using the Secondary color (#FDF2F0) as a subtle background tint to create "depth" without lifting off the page.
- **Soft Glow:** When a hover state is required (for digital CVs), use a very diffused, low-opacity shadow tinted with the Primary color: `0px 10px 30px rgba(200, 157, 156, 0.1)`.
- **Dividers:** Use hairline dividers (0.5px - 1px) in a lightened version of the Primary color to separate list items or timeline entries.

## Shapes

The shape language is consistently soft.

- **Containers:** All cards and profile image containers use a `1rem` (16px) radius to maintain the skincare-inspired softness.
- **UI Accents:** Small markers like timeline dots or skill bar caps are fully rounded (pill-shaped).
- **Buttons/Chips:** Interactive elements follow a pill-shaped convention to contrast against the more rectangular content cards.

## Components

- **Cards:** Defined by the Secondary background (#FDF2F0) and `rounded-lg` corners. No borders. Use these for distinct sections like "Skills" or "Languages."
- **Timeline:** A minimalist vertical line (1px, Primary color at 30% opacity). Timeline markers are 8px solid dots in the Primary color.
- **Skill Bars:** Progress bars consist of a background track in the Secondary color and a thin (4px) active track in the Primary color.
- **Badges/Chips:** Used for "Interests" or "Tools." Pill-shaped with a 1px Primary color border and label-sm typography.
- **Input Fields (Contact Form):** Only bottom-bordered (1px) to maintain the minimalist, stationery-like feel.
- **Icons:** Use thin-stroke (1px) linear icons. Avoid filled icons as they appear too "heavy" for this aesthetic.