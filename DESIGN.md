---
name: Nordic Climate Systems
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
  on-surface-variant: '#44474d'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7a'
  primary: '#000511'
  on-primary: '#ffffff'
  primary-container: '#0b1f36'
  on-primary-container: '#7587a3'
  inverse-primary: '#b5c8e6'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#0e0200'
  on-tertiary: '#ffffff'
  tertiary-container: '#381300'
  on-tertiary-container: '#dc6100'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e3ff'
  primary-fixed-dim: '#b5c8e6'
  on-primary-fixed: '#081c33'
  on-primary-fixed-variant: '#364861'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783200'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
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
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.015em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
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

This design system establishes a premium, authoritative, and deeply reliable identity for high-end residential and commercial HVAC & Climate Control services. The aesthetic balances engineering precision with welcoming home comfort, replacing outdated, cluttered contractor cliches with crisp architecture, airy negative space, and polished digital interactions.

### Personality & Tone
- **Authoritative & Certified:** Built on deep navy bedrock that conveys technical mastery, veteran trade licensure, and ironclad reliability.
- **Atmospheric Clarity:** Crisp icy cyans and immaculate slate-whites evoke fresh air, thermal comfort, and purified environments.
- **Urgent Yet Calm:** Emergency callouts and priority service triggers use vibrant thermal amber without triggering alarmist chaos.

### Design Movement
**Modern Corporate Precision with Soft Tactile Nuance:** High visual fidelity pairing deep solid surfaces with soft ambient lighting, clean hairline boundary rules, 16px to 24px border radii (`rounded-xl`), and translucent navigation bars.

## Colors

The color palette anchors trust through deep maritime navies, captures climate dynamics with chilled cyan and radiant orange, and ensures absolute readability with crisp slate foundations.

### Palette Hierarchy & Intent

- **Primary (`#0B1F36` - Midnight Navy):** Forms the bedrock of the UI. Used for primary headlines, hero backgrounds, primary navigation surfaces, and high-impact structural blocks.
- **Secondary (`#0284C7` - Arctic Cyan):** Represents air purification, cooling efficiency, and smart climate technology. Applied to feature badges, active tabs, link states, and interactive accents.
- **Tertiary (`#F97316` - Thermal Coral/Amber):** Represents immediate warmth, heating solutions, and critical conversions. Strictly reserved for 24/7 emergency dispatch triggers, booking actions, and primary call-to-action buttons.
- **Neutral (`#0F172A` - Slate Charcoal):** Delivers WCAG AAA contrast for body typography, metadata icons, and subtle structural outlines.

### Supporting Surface Tokens
- `surface-canvas`: `#F8FAFC` (Cool Crisp White)
- `surface-card`: `#FFFFFF` (Pristine Porcelain)
- `surface-subtle`: `#F1F5F9` (Engineered Slate)
- `surface-dark`: `#071526` (Abyssal Navy for footer & night modules)
- `border-hairline`: `rgba(15, 23, 42, 0.08)`

## Typography

The typography uses **Plus Jakarta Sans** across all roles to achieve a blend of geometric precision, modern clarity, and warm accessibility. 

### Scale & Application
- **Display & Large Headlines:** Set with tight tracking (`-0.03em` to `-0.02em`) and heavy weights (700–800) to project confidence and structural authority in hero zones.
- **Body Text:** Kept comfortable with a generous line-height multiplier (1.5x–1.55x) and standard kerning to ensure technical specifications and customer explanations are effortless to read.
- **Labels & Microcopy:** Utilize semi-bold to bold weights with uppercase tracking (`+0.05em`) for diagnostic tags, certification badges, 24/7 service markers, and technical readouts.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system that prioritizes clear horizontal relationships and balanced breathing room.

### Grid Anatomy
- **Desktop (1200px+):** 12 columns, `1.5rem` (24px) gutters, and up to `80rem` (1280px) max-width container with auto-centering.
- **Tablet (768px - 1199px):** 8 columns, `1.5rem` gutters, `2rem` outer padding.
- **Mobile (< 768px):** 4 columns, `1rem` gutters, `1rem` outer canvas padding.

### Sectional Rhythm
- High-level landing sections utilize large vertical gaps (`4rem` to `6rem`) to prevent information overload.
- Service card grids and comparison tables maintain strict internal cell paddings (`space-lg`), separating diagnostic data points clearly.

## Elevation & Depth

Visual hierarchy combines tonal layering with deep, soft ambient shadows tinted with the primary navy hue. Rather than harsh grey drop-shadows, elevation appears atmospheric and dimensional.

### Elevation Levels

- **Level 0 (Flat Ground):** Base canvas background (`#F8FAFC`). Pure flat plane.
- **Level 1 (Subtle Cards & Containers):** Pure white container surfaces (`#FFFFFF`) with a hairline border (`rgba(15, 23, 42, 0.06)`) and ambient shadow:
  `0 2px 4px -1px rgba(11, 31, 54, 0.04), 0 4px 12px -2px rgba(11, 31, 54, 0.05)`
- **Level 2 (Hover States & Dropdowns):** Interactive cards on cursor hover and flyout menus:
  `0 8px 24px -4px rgba(11, 31, 54, 0.08), 0 4px 8px -2px rgba(11, 31, 54, 0.04)`
- **Level 3 (Floating Dispatchers, Modals & Floating Chatbot):** Raised floating tools and fixed emergency contact hubs:
  `0 20px 40px -8px rgba(11, 31, 54, 0.16), 0 1px 3px 0 rgba(11, 31, 54, 0.08)`
- **Frosted Glass (Header Navigation):** `rgba(255, 255, 255, 0.85)` with `backdrop-filter: blur(12px)` and a subtle bottom hairline `rgba(15, 23, 42, 0.08)`.

## Shapes

The system implements a balanced, modern curvature profile (`roundedness: 2`), delivering smooth `16px` to `24px` exterior corners on cards and major layout panels (`rounded-xl` to `rounded-2xl`).

### Corner Radius Tokens
- **Interactive Controls (Inputs, Buttons, Badges):** `8px` (`rounded-md`) to `12px` (`rounded-lg`) for tactile precision.
- **Cards, Service Tiles, Floating Chat Panels:** `16px` (`rounded-xl`) to `20px`, delivering an approachable, premium architectural feel.
- **Pills & Status Indicators:** `9999px` (Full circle/pill) for micro badges, phone call pills, and live dispatcher indicators.

## Components

### Buttons
- **Primary CTA (Emergency & Booking):** Background `tertiary_color_hex` (`#F97316`), text `#FFFFFF`, semi-bold weight. Subtle hover shift to `#EA580C`, with a soft glow `box-shadow: 0 4px 14px rgba(249, 115, 22, 0.35)`.
- **Secondary Action (Cooling & Information):** Background `secondary_color_hex` (`#0284C7`), text `#FFFFFF`, hover `#0369A1`.
- **Outline / Navy Alternate:** Border `1.5px solid #0B1F36`, text `#0B1F36`, background transparent. Hover transforms to `#0B1F36` fill with white text.

### Form Inputs & Lead Capture
- White backgrounds (`#FFFFFF`) with a `1px solid rgba(15, 23, 42, 0.15)` border and `10px` radius.
- Padding: `0.75rem 1rem`. Focus state features a crisp Arctic Cyan ring (`box-shadow: 0 0 0 3px rgba(2, 132, 199, 0.20)`, border-color `#0284C7`).
- Form cards sit on `#FFFFFF` or frosted dark panels with high-contrast labels in `#0B1F36`.

### Service Cards
- Set with `rounded-xl` (16px) radius, white ground, hairline boundary, and Level 1 elevation.
- Includes a top accent chip identifying HVAC categories (e.g., "Air Conditioning", "Heat Pumps", "Indoor Air Quality") in subtle cyan or amber tints.
- Transitions seamlessly to Level 2 elevation on hover with a `-3px` subtle vertical translation.

### Status Chips & Badges
- **Emergency / 24/7 Dispatch:** Amber-tinted background (`rgba(249, 115, 22, 0.12)`), text `#EA580C`, with a pulsing red/orange dot indicator.
- **Certified / Diagnostic Pill:** Cyan-tinted background (`rgba(2, 132, 199, 0.12)`), text `#0284C7`.

### Floating Chatbot Container
- Anchored to bottom right with `space-lg` margin.
- Fixed container dimensions: `380px` wide, `560px` max height.
- Header styled in Midnight Navy (`#0B1F36`) with live online status indicators (green pulsing badge) and agent certification details.
- Body surface utilizes `#F8FAFC` slate-white canvas with pure white elevated message bubbles and Arctic Cyan accent send triggers.
- Trigger icon button: 60px circular pill with Thermal Amber accent and Level 3 ambient shadow.