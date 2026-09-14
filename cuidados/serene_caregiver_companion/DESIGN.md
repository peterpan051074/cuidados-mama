---
name: Serene Caregiver Companion
colors:
  surface: '#faf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#faf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f0'
  surface-container: '#efeeea'
  surface-container-high: '#e9e8e4'
  surface-container-highest: '#e3e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#404944'
  inverse-surface: '#2f312e'
  inverse-on-surface: '#f2f1ed'
  outline: '#707974'
  outline-variant: '#bfc9c3'
  surface-tint: '#2c6954'
  primary: '#10533f'
  on-primary: '#ffffff'
  primary-container: '#2e6b56'
  on-primary-container: '#aae9ce'
  inverse-primary: '#95d3ba'
  secondary: '#426276'
  on-secondary: '#ffffff'
  secondary-container: '#c3e4fb'
  on-secondary-container: '#47677a'
  tertiary: '#7b3206'
  on-tertiary: '#ffffff'
  tertiary-container: '#9a491e'
  on-tertiary-container: '#ffd2bf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f0d5'
  primary-fixed-dim: '#95d3ba'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#0d513d'
  secondary-fixed: '#c6e7fe'
  secondary-fixed-dim: '#aacbe1'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#2a4a5d'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb694'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#793105'
  background: '#faf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2df'
typography:
  display-metric:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.03em
  display-metric-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-metric:
    fontFamily: Space Grotesk
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
  gutter: 1rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

The design system addresses the deeply human, vulnerable, and responsible space of elder home care. The product connects families and caregivers around daily routines, attendance validation, tasks, and monthly settlement transparency. 

The emotional tone is calm, reassuring, dignified, and frictionless. Interfaces must remove anxiety from care logistics rather than add administrative overhead. The visual language blends warm tactile minimalism with clear utilitarian legibility: high readability at a glance, generous touch targets, gentle natural surfaces, and honest feedback.

- **Design Philosophy:** Humanist Warmth Meets Clear Structure. Avoid clinical coldness and sterile corporate patterns. Use soft organic tones, ample breathing room, gentle physical depth, and clear contrast cues.
- **Target Audience:** Multi-generational family members (adult children tracking their parents' care) and in-home professional caregivers logging shifts on mobile devices under varying lighting conditions and busy schedules.

## Colors

The color palette is derived from natural, grounded elements that evoke health, trust, domestic warmth, and stability:

- **Primary (`#2E6B56` - Deep Sage Green):** Symbolizes health, restorative care, balance, and confirmed presence. Used for primary calls-to-action, success/confirmed badges, completed attendance records, and active primary navigations.
- **Secondary (`#3A5A6D` - Slate Blue):** Represents steady responsibility, financial record-keeping, and reliable coordination. Used for secondary actions, time stamps, summary statistics, and structured card headers.
- **Tertiary (`#C2683A` - Warm Terracotta/Amber):** Used intentionally for alerts, pending payments, missing shift confirmations, urgent medication reminders, and pending checklists without evoking harsh clinical panic.
- **Neutral Surface (`#F8F7F3` - Warm Paper Canvas):** A soft, eye-resting warm white that eliminates harsh glare while providing natural warmth. Elevated container cards sit on `#FFFFFF`, with borders and dividers rendered in `#E7E5DC`.
- **Text & Contrast:** Primary text is set in `#1C2520` (near-black with a subtle forest tint) to achieve WCAG AAA compliance against warm paper surfaces. Secondary muted text uses `#526058`.

## Typography

The type system prioritizes effortless legibility, especially for elderly family members or caregivers reading while on their feet:

- **Primary Typeface (`Plus Jakarta Sans`):** Selected for its friendly, rounded geometry, wide apertures, and exceptional readability at smaller mobile sizes. It provides warmth without compromising institutional trust.
- **Metric & Numerical Typeface (`Space Grotesk`):** Paired deliberately for counters, day tallies, currency units, and hours. Its tabular figures and distinct geometric forms prevent digit confusion (e.g., distinguishing 0 from O, 1 from 7, and 8 from 3).
- **Hierarchy Rules:** Large key metrics (such as days attended, remaining days, balance due) use dedicated display tokens with high-contrast weight. Descriptive sub-labels are placed in uppercase small tracker text directly beneath numbers for immediate scanning.

## Layout & Spacing

The layout is built for mobile-first single-handed operation, relying on a 4-column mobile grid expanding to an 8-column tablet grid:

- **Touch Reachability:** All critical action items (check-in, check-out, record validation, call family) are positioned within the lower two-thirds of the viewport ("the thumb zone").
- **Card Margins & Safe Areas:** The default screen margin is `1.25rem` (20px), ensuring touch elements stay well clear of device bezel curves and gesture bars.
- **Spacing Rhythm:** Standard spacing adheres to multiples of `0.25rem` (4px/8px grid system). Cards use `1rem` to `1.25rem` internal padding to prevent cramped content. Component gaps within lists stay fixed at `0.75rem` to `1rem` to clearly delineate separate calendar days and status rows.

## Elevation & Depth

Visual hierarchy uses a tactile, soft-layered approach that conveys stability without relying on heavy skeuomorphic shading or cold flat borders:

- **Surface Layering:**
  - **Base Canvas (`#F8F7F3`):** Underlying warm background for screens.
  - **Cards & Sheets (`#FFFFFF`):** Base components float over the background canvas with a soft `1px` tinted border (`#E7E5DC`) and an ambient shadow: `0 3px 12px -2px rgba(46, 107, 86, 0.05)`.
  - **Elevated Modals & Floating Trays:** Used for daily confirmations and shift logging sheets: `0 12px 32px -4px rgba(28, 37, 32, 0.10)`.
- **Interactive State Depth:** When a user taps an actionable card or toggle, it provides a slight inset or immediate optical scale reduction (`0.98`) to deliver tactile feedback that an action has been committed.

## Shapes

The design system implements a balanced rounded shape language (`roundedness: 2`):

- **Cards & Containers:** Default corner radius is `1rem` (16px), giving surfaces an organic, approachable feel.
- **Pills & Status Badges:** Fully rounded (`9999px`) to create an immediate visual contrast against rectangular structural cards.
- **Buttons & Input Controls:** Uses `0.75rem` to `1rem` corner radiuses, ensuring targets feel pressable and comfortable for thumb interaction.
- **Progress Bars & Sliders:** Pill-ended (`9999px`) caps for smooth progression indicators tracking monthly attendance days.

## Components

### 1. Buttons & Main Actions
- **Primary Tap Bar:** Minimum touch height of 52px. Full-width or dominant card-width. Background: `#2E6B56`; Text: `#FFFFFF` bold. Slight drop shadow tinted with sage.
- **Secondary Action:** Minimum height 48px. Background: `#EAECE8`; Text: `#2E6B56`.
- **Destructive/Cancel:** Transparent background with `#C2683A` border and text.

### 2. Binary Segmented Controls (Sí / No / Asistió)
- High-contrast toggle container with a warm muted frame (`#EAE8DF`).
- Active "Sí / Asistió": `#2E6B56` solid background with crisp white typography and a soft green checkmark icon.
- Active "No / Ausente": `#C2683A` solid background with crisp white typography.
- Neutral/Unchecked State: `#FFFFFF` surface with `#526058` text. Minimum tap target is 48px high by 50% container width.

### 3. Metric Summary Cards
- White rounded cards (`16px` radius) with `1.25rem` padding.
- Displays large tabular numbers (`36px-44px`) via the metric font.
- Subtitle positioned immediately below with an icon prefix (e.g., calendar icon, checkmark, cash note).
- Color accents: Sage green border highlight for "Días Cumplidos", Terracotta/Amber accent for "Pendientes de Aprobación" or "Pago Pendiente".

### 4. Status Badges & Chips
- **Pagado / Confirmado:** Pill badge, background `#E5EFEA`, label `#1B4A3A`, bold checkmark icon.
- **Pendiente:** Pill badge, background `#F8EFEA`, label `#8E441D`, clock/warning icon.
- **Día de Descanso:** Pill badge, background `#EEF2F4`, label `#3A5A6D`.

### 5. Daily Attendance List Item
- Structured row card representing a single calendar day.
- Left column: Large date number (`20`) with three-letter day code (`LUN`) stacked in slate blue.
- Center column: Caregiver shift hours (`08:00 - 16:00`) and caregiver signature/note preview.
- Right column: Tap-friendly quick toggle button or status pill badge.

### 6. Notes & Incident Input Fields
- Generous text area with `12px` interior padding, light `#FFFFFF` background, and explicit `#D1CEBE` borders.
- Focused state: `#2E6B56` border with a subtle `2px` focus halo (`rgba(46, 107, 86, 0.15)`).
- Clear action button to record voice notes or quick pre-selected tags (e.g., "Medicación tomada", "Paseo realizado", "Comida completa").