---
name: Kinetic Minimalist
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#5b403f'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#8f6f6e'
  outline-variant: '#e4bebc'
  surface-tint: '#bb152c'
  primary: '#b7102a'
  on-primary: '#ffffff'
  primary-container: '#db313f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3b1'
  secondary: '#485f84'
  on-secondary: '#ffffff'
  secondary-container: '#bbd3fd'
  on-secondary-container: '#445a7f'
  tertiary: '#006860'
  on-tertiary: '#ffffff'
  tertiary-container: '#008379'
  on-tertiary-container: '#f3fffc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#b0c7f1'
  on-secondary-fixed: '#001b3c'
  on-secondary-fixed-variant: '#30476a'
  tertiary-fixed: '#8cf4e8'
  tertiary-fixed-dim: '#6fd8cc'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#00504a'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system focuses on high-performance clarity and athletic energy. It is tailored for a Home Gym & Fitness Coaching studio where the interface acts as a silent partner to the physical workout. The brand personality is disciplined yet motivating, utilizing vast amounts of white space to reduce cognitive load during high-intensity training.

The design style is **Minimalism** infused with **High-Contrast** accents. By stripping away unnecessary decorative elements and complex animations, the system ensures that the user's focus remains entirely on their metrics and coaching cues. The emotional response should be one of professional reliability and immediate readiness to move.

## Colors

The palette is restricted to drive maximum impact through the primary "Kinetic Red." 

- **Primary (#E63946):** Used for critical call-to-actions, active progress states, and key highlights. It represents energy and urgency.
- **Secondary (#1D3557):** A deep navy used for grounding elements, navigation bars, and heavy headings to provide a sense of stability and professionalism.
- **Neutral (#F8F9FA):** The foundation of the UI. This off-white ensures the screen remains easy on the eyes while providing a clean backdrop for the primary red.
- **Text (#111827):** A near-black neutral for maximum legibility and contrast against the light backgrounds.

## Typography

This design system utilizes **Inter** exclusively to maintain a systematic, utilitarian aesthetic. The type scale is aggressive in its weight distribution—using "Extra Bold" for primary metrics and headings to convey strength, while maintaining a clean "Regular" weight for instructional content. 

Label styles should use uppercase with slight letter-spacing to distinguish metadata from body text. For mobile screens, display sizes scale down to prevent awkward line breaks in workout titles, ensuring instructions remain glanceable from a distance.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a strict 8px spacing rhythm. White space is treated as a functional element rather than a void, used to group related exercises and separate recovery periods.

- **Mobile:** 4-column grid with 16px side margins. Elements are primarily stacked vertically to facilitate one-handed use during workouts.
- **Desktop:** 12-column grid with 40px side margins and a maximum container width of 1280px to prevent line lengths from becoming unreadable.
- **Rhythm:** Use `stack-lg` (32px) between major sections and `stack-md` (16px) for internal component spacing (e.g., between a label and an input).

## Elevation & Depth

To maintain the minimal aesthetic, depth is achieved through **Tonal Layers** and very light **Ambient Shadows**. 

- **Level 0 (Base):** The neutral background (#F8F9FA).
- **Level 1 (Cards/Surfaces):** Pure white (#FFFFFF) with a very soft, high-diffusion shadow (0px 4px 20px rgba(0,0,0,0.04)).
- **Level 2 (Interactive):** When hovered or active, elements may increase shadow slightly (0px 8px 30px rgba(0,0,0,0.08)) to indicate tangibility.

Avoid heavy borders or dark drop shadows. Use 1px borders in a light gray only when elements need separation on a pure white surface.

## Shapes

The shape language is defined by **Rounded (8px)** corners. This radius provides a modern, approachable feel that softens the "aggressive" nature of the primary red and bold typography. 

- **Small Components:** Checkboxes and small tags use 4px (Soft).
- **Standard Components:** Buttons, input fields, and cards use 8px (Rounded).
- **Large Components:** Hero sections or large image containers use 16px (Rounded-LG).
- **Circular Elements:** Progress rings and profile avatars remain fully circular.

## Components

- **Buttons:** Primary buttons are solid Kinetic Red with white text. Secondary buttons use a transparent background with a Kinetic Red 2px border. Use large padding (16px 32px) to ensure they are easy to tap with sweaty hands.
- **Cards:** White backgrounds, 8px corner radius, and Level 1 ambient shadows. Use for workout summaries and coach profiles.
- **Input Fields:** Minimalist design with a 1px light gray border that transitions to Kinetic Red on focus. Labels should always be visible above the field.
- **Chips/Tags:** Used for "Difficulty Level" or "Equipment Needed." Use a light tint of the primary color with dark text for high legibility.
- **Progress Indicators:** Use thick strokes for progress bars and rings to emphasize achievement.
- **Lists:** Clean rows with 1px bottom dividers. Ensure a minimum height of 64px for list items to maintain touch-target accessibility.