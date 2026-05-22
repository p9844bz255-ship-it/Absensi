---
name: Premium Attendance
colors:
  surface: '#faf9fe'
  surface-dim: '#dad9df'
  surface-bright: '#faf9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f8'
  surface-container: '#eeedf3'
  surface-container-high: '#e9e7ed'
  surface-container-highest: '#e3e2e7'
  on-surface: '#1a1b1f'
  on-surface-variant: '#4d4732'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f1f0f5'
  outline: '#7e775f'
  outline-variant: '#d0c6ab'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#e9c400'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5d5e63'
  on-tertiary: '#ffffff'
  tertiary-container: '#d9d9de'
  on-tertiary-container: '#5d5f63'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e7'
  tertiary-fixed-dim: '#c6c6cb'
  on-tertiary-fixed: '#1a1c1f'
  on-tertiary-fixed-variant: '#45474b'
  background: '#faf9fe'
  on-background: '#1a1b1f'
  surface-variant: '#e3e2e7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-padding: 20px
  stack-gap-lg: 24px
  stack-gap-md: 16px
  stack-gap-sm: 8px
  card-internal-padding: 16px
---

## Brand & Style
The design system is built on a foundation of "Premium Functionalism." It targets educational administrators and educators who require a high-reliability tool that feels sophisticated rather than institutional. 

The visual style is **Modern Minimalism** with a focus on high-clarity information density. It utilizes a refined color palette of whites and soft grays to provide a "breathable" workspace, while a singular gold accent elevates the interface to a premium tier. The emotional response is one of calm, professional confidence. Subtle glassmorphism is applied to key informative cards to add depth without cluttering the mobile viewport.

## Colors
This design system operates in a Light Mode environment to maintain maximum legibility and a sense of cleanliness.

*   **Primary (Gold):** #FFD700. Used exclusively for primary actions, active states, and critical information highlights. It represents value and precision.
*   **Neutral Background:** #F2F2F7. A soft, cool-toned gray used for the main application background to make pure white cards (#FFFFFF) pop.
*   **Surface Colors:** High-purity white is used for all interactive containers and data cards.
*   **Typography Colors:** Deep charcoal (#1A1A1A) for primary text to ensure high contrast, and medium gray (#8E8E93) for secondary metadata and captions.

## Typography
The system uses **Plus Jakarta Sans** for its contemporary feel and excellent legibility at small scales. All text is localized in **Indonesian**.

Headlines use semi-bold and bold weights to establish a clear hierarchy against the minimalist background. Body text is set with generous line-height to prevent eye strain during long attendance sessions. Uppercase labels are used sparingly for category headers (e.g., "TABEL", "RINGKASAN") to create a professional, structured look.

## Layout & Spacing
The layout follows a **fluid-to-safe-area** model specifically optimized for mobile devices. 

*   **Margins:** A consistent 20px horizontal margin is maintained on all screens.
*   **Rhythm:** An 8px base grid is used for all internal spacing.
*   **Verticality:** Content is stacked vertically with 16px gaps between primary cards. Sections (like "Ringkasan Absensi") are separated by 24px to provide clear visual breathing room.
*   **Safe Areas:** Interaction elements like floating action buttons or bottom navigation are positioned with a 32px offset from the bottom edge to clear system gestures.

## Elevation & Depth
Hierarchy is established through **Tonal Layering** and **Soft Ambient Shadows**.

*   **Level 0 (Background):** Solid #F2F2F7.
*   **Level 1 (Cards):** White surfaces with a very soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.04)). This makes the cards appear to float slightly above the gray background.
*   **Level 2 (Active Elements):** Primary buttons and active status chips use the Gold (#FFD700) fill without shadows, relying on color-contrast for prominence.
*   **Glassmorphism:** Profile headers utilize a backdrop blur (20px) with a 70% white opacity overlay to create a premium, layered aesthetic over student imagery.

## Shapes
The shape language is defined by large, "squircle-like" corners that feel friendly and approachable.

*   **Primary Containers:** Use a 24px (rounded-xl) radius to enclose card content.
*   **Buttons & Chips:** Use a 12px or fully pill-shaped radius depending on the interaction type.
*   **Input Fields:** Follow the 16px radius of smaller cards for consistency.
*   **Avatars:** Always circular to provide a soft contrast to the rectangular layout of the cards.

## Components

### Buttons
*   **Primary:** Solid Gold (#FFD700) with deep charcoal text. No shadow.
*   **Secondary/Ghost:** White background with a 1px soft gray border.
*   **Icon Buttons:** Circular 40x40px containers with 20px icons, using a subtle glass effect when placed over imagery.

### Attendance Chips
*   **Active (Hadir):** Gold background, charcoal text.
*   **Inactive (Izin, Sakit, Alpa):** White background, 1px light gray border, charcoal text.
*   **Shape:** Pill-shaped for high touch-target visibility.

### Cards
*   **Student Row:** A horizontal white card containing a circular avatar, student name, and a row of attendance chips.
*   **Summary Card:** Uses icons with colored backgrounds (Gold for Hadir, Brown for Izin) to allow for quick scanning of data.

### Inputs
*   **Dropdown/Filters:** White backgrounds with 16px corner radius. Include a chevron-down icon. Indonesian labels (e.g., "Pilih Kelas").
*   **Search Bar:** Pill-shaped with a glassmorphic background or solid white with a subtle 1px border.

### Imagery
*   **Student Profiles:** High-resolution, realistic stock photography with neutral backgrounds. Images should be cropped to 1:1 circles or soft-edged squares.