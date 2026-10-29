---
name: Horizonte Viajes
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434652'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737783'
  outline-variant: '#c3c6d4'
  surface-tint: '#2b5bb5'
  primary: '#003178'
  on-primary: '#ffffff'
  primary-container: '#0d47a1'
  on-primary-container: '#a1bbff'
  inverse-primary: '#b0c6ff'
  secondary: '#a73a00'
  on-secondary: '#ffffff'
  secondary-container: '#fd651e'
  on-secondary-container: '#571a00'
  tertiary: '#003d29'
  on-tertiary: '#ffffff'
  tertiary-container: '#00573b'
  on-tertiary-container: '#5cd19f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b0c6ff'
  on-primary-fixed: '#001945'
  on-primary-fixed-variant: '#00429c'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7f2b00'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system is structured for a modern, high-confidence travel and booking platform. It addresses travelers seeking friction-free exploration, transparent pricing, and reassuring confirmation experiences.

### Brand Personality & Emotional Impact
- **Trust & Reliability:** Visual weight communicates stability through deep nautical blues, structured card surfaces, and unmistakable data clarity.
- **Warmth & Guidance:** High-contrast amber accents direct attention to critical actions without overwhelming the travel content.
- **Calm Efficiency:** Generous whitespace, precise typography, and low visual noise reduce cognitive fatigue during complex booking flows.

### Visual Style
- **Modern Clean with Tactile Surface Clues:** Combines foundational minimalism, crisp low-contrast borders (`#E2E8F0`), and multi-layer soft shadows to elevate functional booking components above neutral backdrops.
- **Information Architecture:** Prioritizes structured scanning: bold pricing figures, distinct status markers, step-by-step progress signposts, and ticket/voucher affordances.

## Colors

The palette balances authoritative maritime blues with energetic, conversion-focused warm tones and crystal-clear feedback indicators.

### Roles & Semantic Application
- **Primary (`#0D47A1`):** Represents structure, navigation bars, section headers, primary interactive states, and core branding elements.
- **Secondary (`#EA580C`):** Reserved strictly for high-conversion actions: booking triggers, checkout buttons, special price tags, and dynamic notifications.
- **Tertiary / Success (`#059669`):** Indicates completed booking steps, confirmed vouchers, verified listings, and availability status.
- **Neutral Primary (`#0F172A`):** Deep slate used for maximum typographic contrast on headers, flight times, and critical numeric values.
- **Neutral Secondary (`#334155`):** Mid-tone slate for supporting body copy, helper captions, and metadata.
- **Border & Dividers (`#E2E8F0`):** Subtle boundaries that separate panels, form controls, and itinerary segments without cluttering the viewport.
- **Surfaces (`#FFFFFF` and `#F8FAFC`):** Pure white for elevated cards and modals; soft slate-tinted white for root background depth.

## Typography

The design system standardizes on **Plus Jakarta Sans** across all roles to ensure geometric balance, high legibility at micro-sizes (such as airport codes and dates), and approachable confidence in editorial travel headers.

### Hierarchy Guidelines
- **Numeric Figures & Pricing:** Use `headline-lg` or `headline-md` paired with `label-sm` super-scripting to make room rates and flight fares scannable within 200 milliseconds.
- **Airport Codes & Tracking References:** Apply tabular figures (`font-variant-numeric: tabular-nums`) alongside `label-lg` with uppercase transformation and slight tracking (`letterSpacing: 0.04em`).
- **Body & Captions:** Reserve `body-md` for standard travel descriptions, terms, and form fields; use `body-sm` strictly for disclaimers, baggage notes, and cancellation policy footnotes.

## Layout & Spacing

A 12-column responsive fluid grid governs the screen system, adapting down to 8 columns on tablets and 4 columns on mobile viewports.

### Grid & Breakpoints
- **Desktop (1200px+):** 12 columns, `margin: 2rem`, `gutter: 1.5rem`. Max container width capped at `1280px` centered for content clarity.
- **Tablet (768px - 1199px):** 8 columns, `margin: 1.5rem`, `gutter: 1.25rem`. Booking sidebars collapse into sticky footer bottom sheets.
- **Mobile (320px - 767px):** 4 columns, `margin-mobile: 1rem`, `gutter-mobile: 1rem`. Form elements stack vertically into single columns.

### Sectional Rhythm
- **Search Hero:** Positioned directly below the primary navigation, breaking out of the container with negative margin overlays to seamlessly integrate into visual destination photography.
- **Checkout Flow:** Structured as an asymmetric 8:4 split column grid (8 columns for form inputs, 4 columns for the sticky summary card).

## Elevation & Depth

Visual hierarchy uses a refined 3-tier elevation model combining low-contrast border boundaries with warm tinted ambient shadows.

### Elevation Levels
- **Level 0 (Flat / Canvas):** Surface color `#F8FAFC`, no shadow, 0 border. Used for page roots and background containers.
- **Level 1 (Surface Cards & Inputs):** Surface `#FFFFFF`, border `1px solid #E2E8F0`, shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.06), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`. Used for destination cards, search containers, and default fields.
- **Level 2 (Hovered Cards & Sticky Summary):** Surface `#FFFFFF`, border `1px solid #CBD5E1`, shadow: `0 10px 15px -3px rgba(13, 71, 161, 0.08), 0 4px 6px -4px rgba(13, 71, 161, 0.03)`. Used for active itinerary cards, focused search dropdowns, and sticky checkout summaries.
- **Level 3 (Modals, Popovers & Floating Search Bar):** Surface `#FFFFFF`, border `none`, shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`. Used for date-pickers, guest-count popovers, and print preview dialogs.

## Shapes

The roundedness token is set to **`2` (Rounded)**:
- Standard elements (buttons, text inputs, chips) carry a base radius of `0.5rem` (8px).
- Cards, booking summary panels, and destination containers use `rounded-lg` at `1rem` (16px).
- Modals, prominent hero search hubs, and voucher components use `rounded-xl` at `1.5rem` (24px).
- Status badges, pill tags, and step-indicator nodes use fully circular edges (`rounded-full` / `9999px`).

## Components

### Buttons
- **Primary Action (Book / Confirm):** Background `#EA580C`, text `#FFFFFF`, font-weight `600`, border-radius `0.5rem`, padding `0.75rem 1.5rem`. Hover state transitions to `#C2410C` with a micro-elevation lift (`translate-y: -1px`).
- **Brand Action (Search / Filter):** Background `#0D47A1`, text `#FFFFFF`, hover `#1E40AF`.
- **Secondary / Outline:** Background transparent, border `1.5px solid #0D47A1`, text `#0D47A1`, hover `#EFF6FF`.
- **Ghost:** Transparent background, text `#334155`, hover background `#F1F5F9`.

### Chips & Badges
- **Tag / Filter Chip:** Pill shape (`9999px`), padding `0.375rem 0.875rem`, background `#F1F5F9`, border `1px solid #E2E8F0`, text `#334155`. Active state: background `#EFF6FF`, border `#0D47A1`, text `#0D47A1`.
- **Status Badges:** Small (`label-sm`), uppercase, bold.
  - *Confirmed / Available:* Background `#ECFDF5`, text `#059669`.
  - *Discount / Hot Deal:* Background `#FFF7ED`, text `#C2410C`.

### Destination Cards
- Standard `rounded-lg` container with Level 1 elevation transitioning to Level 2 on hover.
- Upper 55% dedicated to an aspect-ratio-locked imagery wrapper with an inset gradient overlay for readability.
- Badges anchored top-left (e.g., "Vuelo + Hotel"); heart/favorite action top-right with blurred backdrop glass (`rgba(255, 255, 255, 0.8)`).
- Lower body features destination title (`headline-sm`), duration/rating caption, and clear price hierarchy: `label-sm` "Desde" stacked over `headline-md` price in `#0F172A`.

### Integrated Search Bar
- Segmented container with internal dividers (`1px solid #E2E8F0`).
- Divided into 4 distinct touchpoints: *Origen/Destino*, *Fechas (Ida / Vuelta)*, *Pasajeros & Clase*, and the final action trigger.
- Active segments expand interactive popover sheets using Level 3 elevation with rounded calendar controls.

### 3-Step Booking Stepper
- Horizontal bar centered over checkout screens.
- Step indicators: `32px` circular nodes connected by a `2px` track.
  - *Completed:* Background `#059669`, white checkmark icon, track `#059669`.
  - *Current:* Background `#0D47A1`, white step numeral, track `#E2E8F0`, label in bold `#0F172A`.
  - *Upcoming:* Background `#E2E8F0`, text `#64748B`, track `#E2E8F0`.

### Form Fields (2-Column Checkout)
- Standardized `0.5rem` radius, border `1px solid #CBD5E1`, background `#FFFFFF`, padding `0.75rem 1rem`.
- Focus state: border `#0D47A1`, ring `3px solid rgba(13, 71, 161, 0.15)`, outline none.
- Error state: border `#DC2626`, helper caption in `#DC2626`.
- Right-hand floating summary panel remains sticky (`top: 2rem`) with price breakdowns, taxes, discounts, and cancellation policy reassurance.

### Voucher / Confirmation Card
- Physical ticket aesthetic: white card container split horizontally or vertically by a scalloped notch cut-out and dashed divider line (`border-dashed border-slate-300`).
- Left / Top zone: Booking reference code (alphanumeric `Space Mono` or `Plus Jakarta Sans 700`), QR code verification box, route details with flight/bus icon vectors.
- Right / Bottom zone: Passenger names, seat assignments, baggage allowance badges, and secondary action buttons (`Imprimir Itinerario`, `Añadir a Apple/Google Wallet`).