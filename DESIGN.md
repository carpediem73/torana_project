---
name: Calm Intelligence
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
  secondary: '#006a63'
  on-secondary: '#ffffff'
  secondary-container: '#99efe5'
  on-secondary-container: '#006f67'
  tertiary: '#006194'
  on-tertiary: '#ffffff'
  tertiary-container: '#007bb9'
  on-tertiary-container: '#fdfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#9cf2e8'
  secondary-fixed-dim: '#80d5cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#00504a'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
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
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  mono-metric:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
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
  margin-desktop-max: 72rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  section-desktop: 6.25rem
  section-mobile: 4rem
---

## Brand & Style

This design system establishes an architectural, evidence-grounded visual environment tailored for institutional artificial intelligence. Drawing inspiration from Google's high-whitespace utility, academic research frameworks, and modern discovery portals, the aesthetic prioritizes cognitive ease, calm authority, and frictionless information retrieval.

The visual ethos rejects dark-mode neon tropes and synthetic glass glows in favor of a bright, disciplined canvas where typography, precision borders, and intentional teal accents do the structural work. Every layout element serves orientation or execution; decorative surplus is deliberately excluded. The resulting atmosphere feels institutional yet agile—conveying peer-reviewed rigor, operational resilience, and enduring trust.

## Colors

The palette relies on high-purity slate neutrals structured across a deliberate tonal hierarchy, activated by deep, clinical teals rather than aggressive tech primaries.

- **Primary Canvas & Surfaces**: The base canvas operates on Slate-50 (`#F8FAFC`), while cards, data surfaces, and focal containers utilize absolute white (`#FFFFFF`) to produce clear visual separation through value rather than heavy shading.
- **Text & Hierarchy**: Slate-900 (`#0F172A`) commands display titles and primary body text with maximum legibility. Slate-700 (`#334155`) governs secondary copy and descriptive text. Slate-500 (`#64748B`) handles tertiary labels, timestamps, and placeholder states.
- **Structural Lines**: Borders and dividers strictly use Slate-200 (`#E2E8F0`), creating a crisp 1px matrix across all card surfaces.
- **Primary Accent**: Deep Teal (`#0D9488`) anchors active interaction zones, key buttons, and active tabs, with Teal-800 (`#0F766E`) reserved for hover states and institutional focus areas.
- **System Diagnostics**:
  - Success: Emerald (`#059669`) with an ultra-light tint (`#ECFDF5`) for resolved workflows and verified credentials.
  - Warning: Amber (`#D97706`) with warm tint (`#FFFBEB`) for caution states and pending syncs.
  - Informational: Sky/Teal (`#0284C7`) with cool tint (`#F0F9FF`) for algorithmic notes and parameter callouts.

## Typography

Plus Jakarta Sans provides a cohesive foundation across all display, body, and micro-copy touchpoints. Its balanced geometry combines humanistic openness with structural precision, avoiding both sterile corporate uniformity and excessive informality.

- **Hero & Headline Scale**: Display levels utilize negative tracking to consolidate horizontal footprint at larger scales, creating an authoritative headline presence.
- **Body & Information Consumption**: The body text is tuned for extended reading comfort with a 1.5× baseline multiplier on `body-md` and `body-sm`. Paragraphs should be limited to 68 characters per line maximum.
- **Labels & Micro-Indicators**: Badges, status chips, and metadata make consistent use of `label-sm` with tight tracking and a medium-to-semibold weight, ensuring rapid scanning across dense tabular and card interfaces.

## Layout & Spacing

The layout is structured around a centered, 12-column responsive grid with a maximum content container width of 1152px (`72rem`), prioritizing focal balance over edge-to-edge sprawl.

- **Vertical Cadence**: Major landing page sections maintain expansive vertical clearance of 80px to 100px (scaling down to 64px on viewport widths below 768px). This creates an unhurried, library-grade browsing rhythm.
- **Column Configurations**:
  - Desktop (1024px+): 12 columns, 24px (`1.5rem`) gutter, 32px canvas margins. Typical compositions split cleanly into 6:6 (comparisons), 4:4:4 (feature grids), or 8:4 (search engine & contextual panel).
  - Tablet (768px - 1023px): 8 columns, 20px gutter, 24px canvas margins.
  - Mobile (<768px): 4 columns, 16px (`1rem`) gutter, 16px canvas margins. Multi-column cards collapse to single-column vertical flows.
- **Padding Principles**: Grouped card interiors utilize `1.5rem` (`24px`) padding consistently; nested metadata containers compress to `0.75rem` (`12px`) or `1rem` (`16px`).

## Elevation & Depth

Visual hierarchy is communicated via clean tonal contrast and delicate borders, avoiding pronounced or colorful drop shadows.

- **Surface Levels**:
  - `Base`: Canvas background in Slate-50 (`#F8FAFC`).
  - `Level 1 (Resting Cards)`: `#FFFFFF` card body with a 1px uniform perimeter in Slate-200 (`#E2E8F0`) and an ambient micro-diffused shadow (`0 1px 3px 0 rgba(15, 23, 42, 0.04)`).
  - `Level 2 (Interactive Hover / Modals)`: Card surfaces scale down the border opacity while applying a soft, extended ambient drop (`0 8px 24px -4px rgba(15, 23, 42, 0.06), 0 2px 6px -1px rgba(15, 23, 42, 0.03)`).
- **Search & Query Elevation**: The central query/command field utilizes an inset surface highlight paired with a delicate, focused ring: an interior white background flanked by a 1px border (`#CBD5E1`) expanding smoothly on focus to a 3px outer ring in Teal at 15% opacity (`rgba(13, 148, 136, 0.15)`).

## Shapes

The geometric framework balances human comfort with architectural rigor using medium radii:

- **Cards & Primary Modules**: Styled at 12px to 16px (`0.75rem` to `1rem`) corner radius. This softens technical density without creating toy-like or bubble-shaped aesthetics.
- **Interactive Controls**: Buttons, text inputs, and filter chips use a unified 8px (`0.5rem`) radius to preserve crisp structural alignment in forms and rows.
- **Status Pills & Indicators**: Metric chips and status indicators use a full circular radius (`9999px`) to immediately distinguish informative data badges from interactive actionable cards.

## Components

### Buttons
- **Primary**: Solid background `#0D9488`, foreground `#FFFFFF`, font `label-md`. 8px border radius. Padding: 10px 20px. Hover transitions to `#0F766E` with no dimensional offset.
- **Secondary / Outline**: `#FFFFFF` background, 1px border `#E2E8F0`, text `#334155`. Hover background `#F8FAFC` with border `#CBD5E1`.
- **Ghost**: Transparent background, text `#0D9488`. Hover background `#F0FDFA` (Teal-50).

### Cards & Feature Tiles
- Background `#FFFFFF`, 1px solid `#E2E8F0`, 16px border radius, 24px interior padding.
- Internal headers pair an icon container (36×36px, `#F0FDFA` background, `#0D9488` icon glyph) with `headline-sm` titles.
- Never use multi-color gradient fills behind cards; maintain white grounds to highlight content integrity.

### Input Fields & Search Bars
- Central search/discovery input features a 48px height, 12px border radius, 16px horizontal padding, `#FFFFFF` ground, and 1px `#CBD5E1` border.
- Leading icon in `#64748B`. Placeholder text in `#94A3B8`.
- Focus state activates an outer halo (`0 0 0 3px rgba(13, 148, 136, 0.15)`) with a `#0D9488` border transition.

### Chips & Filter Badges
- **Interactive Filter Chips**: Height 32px, 8px radius, padding 6px 12px. Unselected state uses `#FFFFFF`, 1px border `#E2E8F0`, text `#475569`. Selected state shifts to `#F0FDFA` background, `#0D9488` border, `#0F766E` text with a small teal dot indicator.
- **Read-Only Status Badges**: Pill-shaped (`9999px`), padding 2px 10px, typography `label-sm`.
  - Emerald: background `#ECFDF5`, text `#065F46`.
  - Amber: background `#FFFBEB`, text `#92400E`.
  - Sky/Teal: background `#F0F9FF`, text `#0369A1`.

### Lists & Data Rows
- Row containers separated by 1px horizontal rules in `#F1F5F9`.
- Hover on interactive rows introduces `#F8FAFC` background with a 150ms ease.
- Left-aligned primary attributes paired with monospaced numerical tags and metadata right-aligned in `#64748B`.

### Checkboxes & Radio Controls
- Base 16×16px container with 4px radius (checkbox) or circular (radio).
- Border: 1.5px `#CBD5E1`. Checked state fills `#0D9488` with `#FFFFFF` check/dot mark.