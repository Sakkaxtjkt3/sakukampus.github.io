---
name: Saku Pintar
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
  on-surface-variant: '#3d4a42'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6d7a72'
  outline-variant: '#bccac0'
  surface-tint: '#006c4a'
  primary: '#006948'
  on-primary: '#ffffff'
  primary-container: '#00855d'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dba9'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#4b41e1'
  on-tertiary: '#ffffff'
  tertiary-container: '#645efb'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85f8c4'
  primary-fixed-dim: '#68dba9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#e2dfff'
  tertiary-fixed-dim: '#c3c0ff'
  on-tertiary-fixed: '#0f0069'
  on-tertiary-fixed-variant: '#3323cc'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
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
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for Gen Z university students managing tight daily budgets, meal allowances (uang saku kos), and group splits. The design aesthetic balances playfulness with financial rigor: optimistic, punchy, tactile, and frictionless. 

It draws inspiration from modern neo-fintech and tactile minimalism—avoiding intimidating corporate density in favor of high-legibility cards, energetic badge treatments, and quick-scan budget meters. The emotional goal is to transform budgeting from an anxious chore into an empowering daily check-in. The interface remains crisp and structured: generous spacing, friendly radiuses, purposeful color signaling, and tactile feedback states.

## Colors

The palette uses Emerald (#059669) as the core signal for positive financial health, active savings targets, and secure balances. Warm Tangerine/Amber (#F59E0B) indicates soft thresholds, budget burn rates, and daily limit warnings. Indigo (#4F46E5) serves as an accent for analytics, multi-wallet views, and peer splits.

- **Canvas & Surface Tiers**:
  - `surface-canvas`: `#F8FAFC` (Cool slate tint providing clear separation against card tiles)
  - `surface-card`: `#FFFFFF` (Pristine, high-contrast foreground)
  - `surface-card-subtle`: `#F1F5F9` (Nested modules, receipt containers, breakdown rows)
  - `surface-card-tinted`: `#ECFDF5` (Active success cards and safe-spending containers)
- **Text & Stroke Hierarchy**:
  - `text-primary`: `#0F172A` (Slate 900 for high-contrast numeric values and titles)
  - `text-secondary`: `#475569` (Slate 600 for descriptions and categories)
  - `text-muted`: `#94A3B8` (Slate 400 for timestamps, inactive states, placeholder tokens)
  - `stroke-soft`: `#E2E8F0` (Single-pixel bounding dividers)
  - `stroke-focus`: `#10B981` (Primary interaction rings)
- **Status & Alerts**:
  - `status-danger`: `#EF4444` (Exceeded limits, negative balances)
  - `status-warning`: `#F59E0B` (Approaching 80% daily budget)
  - `status-safe`: `#10B981` (Under budget, positive cashback)

## Typography

Plus Jakarta Sans is utilized across all levels to maintain high geometric clarity, open counters, and a friendly Indonesian-tech aesthetic.

- **Currency & Numerics**: Display scales (`display-xl`, `headline-lg`) feature tabular numbers (`tnum`) for Rupiah currency expressions (e.g., `Rp45.000`), ensuring alignment within transaction sheets and balance widgets.
- **Letter Spacing**: Use `-0.02em` for headlines above 20px to tighten display impact. Body and label sizes maintain `0em` or `+0.01em` for readability at small phone resolutions.
- **Labels & Micro-Tags**: `label-sm` is always styled with full capitalization or clean sentence case within transaction badges and status pills.

## Layout & Spacing

The layout is built around a mobile-first, 4-column grid (375px–430px base canvas), transitioning to an 8-column layout on tablet (640px+) and a constrained 12-column layout capped at 1024px maximum content width on desktop.

- **Margins & Safe Zones**: Mobile layouts preserve `margin` (16px) left and right boundaries with explicit accommodation for modern touch devices: minimum 44px safe-area padding at screen bottoms for navigation bars and sticky action bars.
- **Card Padding**: Primary financial cards utilize `space-lg` (24px) for prominent balances and `space-md` (16px) for itemized budget subcards.
- **Stack Gaps**: Vertical gaps between card sections adhere strictly to `space-md` (16px) to keep modules grouped without visual clutter.

## Elevation & Depth

Visual hierarchy combines clean tonal surfaces, low-contrast ghost outlines, and soft ambient tinted drop shadows. Heavy drop shadows are avoided to keep the interface light and fast.

- **Tier 0 (Base Canvas)**: Flat `#F8FAFC`, no shadow.
- **Tier 1 (Surface Cards & Lists)**: `#FFFFFF` surface accompanied by a single border `1px solid #F1F5F9` and ambient shadow: `0 4px 16px -2px rgba(15, 23, 42, 0.04)`.
- **Tier 2 (Sticky Headers, Interactive Popovers, Active Floating Pills)**: `#FFFFFF` surface with `0 10px 25px -4px rgba(15, 23, 42, 0.08)`.
- **Tier 3 (Modals & Action Drawers)**: `#FFFFFF` layered over a dim backdrop (`rgba(15, 23, 42, 0.4)`), lifted with `0 20px 30px -6px rgba(15, 23, 42, 0.12)`.
- **Active State Depth**: Interactive buttons compress slightly (`transform: scale(0.98)`) and remove low-level drop shadow on press.

## Shapes

The design system employs a generous rounded geometry to remain welcoming and ergonomic for single-thumb mobile usage.

- **Base Components**: Standard inputs, transaction list tiles, and secondary buttons utilize `rounded-lg` (16px / 1rem).
- **Hero Containers & Primary Cards**: Balance cards, budget summary meters, and promotional modules utilize `rounded-xl` (24px / 1.5rem).
- **Pills & Badges**: Micro-tags, category chips, and floating navigation bars adopt fully rounded circular ends (`border-radius: 9999px`).
- **Input Indicators**: Selection checkboxes and radio containers use uniform 6px and 9999px profiles respectively.

## Components

### Buttons
- **Primary**: Solid Emerald (`#059669`) background, text `#FFFFFF`, height 48px, radius 16px, font `label-lg`. Hover/active shift to `#047857`. Full width on mobile bottom sheets.
- **Warning / Action**: Solid Amber (`#F59E0B`) background with text `#0F172A` for critical limit approvals.
- **Secondary**: Surface `#ECFDF5`, text `#059669`, zero border.
- **Ghost / Tertiary**: Transparent background, text `#475569`, border `1px solid #E2E8F0`.

### Chips & Badges
- **Transaction Badges**: Fully rounded pills with 4px vertical, 10px horizontal padding.
  - *Food / Warteg*: Peach/Amber tint (`bg: #FEF3C7`, `text: #B45309`).
  - *Campus / Books*: Indigo tint (`bg: #EEF2FF`, `text: #4338CA`).
  - *Allowance / Masuk*: Mint tint (`bg: #ECFDF5`, `text: #047857`).
- **Filter Chips**: Height 36px, `rounded-full`, text `label-md`. Inactive: `#FFFFFF` with `#E2E8F0` border. Active: `#0F172A` fill with `#FFFFFF` text.

### Cards & Budget Containers
- **Main Balance Card**: `#059669` emerald gradient or pristine `#FFFFFF` card with deep border. Features high-contrast balance font (`display-xl-mobile`), dual-action quick buttons (Top-up, Catat Cepat).
- **Budget Burn Indicator**: A segmented horizontal gauge inside an elevated card showing: "Sisa Hari Ini: Rp25.000 / Rp50.000". Track fill color switches dynamically: Emerald (<75%), Amber (75–99%), Red (>=100%).

### Input Fields
- **Container**: 52px height, `rounded-lg`, border `1.5px solid #E2E8F0`, surface `#FFFFFF`.
- **Focus State**: Border color `#059669`, subtle ring glow `0 0 0 3px rgba(16, 185, 129, 0.15)`.
- **Prefix / Suffix**: Static "Rp" prefix rendered in `headline-sm` with slate muted styling (`#64748B`).

### Transaction List Items
- **Layout**: Row layout with 48px rounded square avatar container (`#F1F5F9`) housing the student-centric category icon (e.g., noodle bowl, bus, notebook).
- **Typography**: Merchant/Note title in `body-md` (`font-weight: 600`), category and time in `body-sm` (`#94A3B8`). Amount right-aligned in `label-lg` with positive cash flows prepended by `+` in `#059669` and spending in `#0F172A`.

### Checkboxes & Radios
- Size 20px × 20px. Unchecked state: `#FFFFFF` with `#CBD5E1` border (1.5px). Checked state: `#059669` fill with an internal white checkmark icon. Radios maintain concentric dot animation with 3px interior spacing.