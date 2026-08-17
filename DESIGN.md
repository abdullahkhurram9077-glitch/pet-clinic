---
name: Serene Vet
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
  on-surface-variant: '#3d4947'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#585d60'
  on-tertiary: '#ffffff'
  tertiary-container: '#707579'
  on-tertiary-container: '#fbfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#dfe3e7'
  tertiary-fixed-dim: '#c3c7cb'
  on-tertiary-fixed: '#171c1f'
  on-tertiary-fixed-variant: '#43474b'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
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
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

This design system is built on a foundation of **Professional Compassion**. It targets pet owners seeking a reliable, high-end veterinary experience that balances medical authority with emotional warmth. 

The aesthetic leans into **Soft Minimalism with Tactile Cues**. It prioritizes extreme clarity and hygiene through expansive whitespace, while using organic rounded shapes and gentle depth to avoid a sterile or clinical feeling. The interface should evoke a sense of calm, safety, and modern efficiency, ensuring users feel their pets are in capable, caring hands.

## Colors

The palette is designed to lower the heart rate of anxious pet owners. 

*   **Primary (Teal):** Used for primary actions, branding, and status indicators. It represents health and vitality.
*   **Secondary (Slate Blue):** Used for typography, iconography, and grounding elements. It conveys stability and medical expertise.
*   **Warm White & Off-White:** The primary background colors. These provide a "clean" feel that is softer on the eyes than pure white, suggesting a welcoming clinic environment.
*   **Semantic Colors:** Use a soft emerald for success, a muted amber for warnings, and a gentle rose for alerts, all maintaining the desaturated, calming profile of the main palette.

## Typography

Inter is utilized for its exceptional legibility and neutral, modern character. 

*   **Headlines:** Use tight letter-spacing and semi-bold weights to create a sense of organized authority.
*   **Body Text:** Set with generous line height to improve readability, especially for medical instructions or pet health records.
*   **Labels:** Small caps or medium weights are used for data visualization and form headers to create a clear information hierarchy.

## Layout & Spacing

The layout follows a **Fluid-Fixed Hybrid** model. Content is contained within a max-width wrapper on desktop to maintain readability, but utilizes fluid percentages for internal grid columns.

*   **Rhythm:** Based on an 8px baseline grid. All padding and margins should be increments of 8px (8, 16, 24, 32, 48, 64).
*   **Whitespace:** Prioritize vertical "breathing room." Use large margins (48px+) between major sections to prevent the UI from feeling cluttered or stressful.
*   **Responsive Behavior:** On mobile, shift to a single-column stack with increased padding within cards to ensure touch targets remain large and accessible.

## Elevation & Depth

This design system uses **Ambient Tonal Elevation**. Depth is communicated through subtle shifts in background saturation and extremely soft, large-radius shadows.

*   **Level 0 (Background):** Surface color (`#FAFAFA`).
*   **Level 1 (Cards/Sections):** White surface with a 1px border (`#E2E8F0`) or a very faint shadow (Y: 2px, Blur: 8px, Opacity: 4% Slate Blue).
*   **Level 2 (Interactive/Floating):** White surface with a medium shadow (Y: 8px, Blur: 24px, Opacity: 8% Slate Blue). Used for hover states and dropdowns.
*   **Overlays:** Use a high-blur (20px) backdrop filter rather than a heavy dark tint to maintain the "hygienic" feel.

## Shapes

The shape language is defined by **Friendly Geometry**. All interactive elements and containers feature soft, generous radii to eliminate "sharpness" and create a welcoming environment.

*   **Standard Components:** Buttons and inputs use the base `rounded` (0.5rem) setting.
*   **Containers:** Cards and modals use `rounded-lg` (1rem) or `rounded-xl` (1.5rem) to emphasize the soft, protective nature of the brand.
*   **Icons:** Use a consistent 2px stroke width with rounded caps and joins to match the typography and corner radii.

## Components

*   **Buttons:** Primary buttons use solid Teal with white text. Secondary buttons use a Slate Blue outline or a ghost style. All buttons have a minimum height of 48px to ensure ease of use on mobile.
*   **Cards:** The centerpiece of the UI. Use cards to group pet information, appointments, and medical history. Cards should have a white background, 16px radius, and a 1px Slate-100 border.
*   **Inputs:** Fields should have a subtle background tint (`#F8FAFC`) and change to a Teal border on focus. Labels should always be visible above the field.
*   **Chips:** Used for pet categories (e.g., "Canine", "Feline") or status (e.g., "Vaccinated"). Use light-tinted backgrounds of the primary color with dark text.
*   **Lists:** Veterinary records should be displayed in "Clean Lists"—rows separated by light horizontal rules with generous 20px vertical padding.
*   **Pet Avatars:** Always use circular masks for pet photos with a 2px Teal border to denote "active" or "selected" status.