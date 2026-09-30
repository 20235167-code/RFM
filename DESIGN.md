---
name: RFM Analytics Workspace
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#ca8100'
  on-tertiary-container: '#3e2400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  metric-value:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  metric-value-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.015em
  code-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
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
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system targets modern data science teams, growth engineers, and executive decision-makers analyzing customer lifecycles, churn dynamics, and cohort values. The emotional tone is authoritative, analytical, and razor-sharp, inspiring confidence through extreme legibility, high data density, and effortless visual parsing.

The aesthetic fuses Corporate Modern with Precision Dark-Tech:
- Ultra-crisp surface separations with near-zero visual clutter.
- High-contrast visual hierarchies prioritizing statistical clarity over decorative fluff.
- Strict chromatic semantics where every hue delivers direct diagnostic meaning regarding segment health and monetary velocity.
- Restrained, engineering-grade feedback states engineered for prolonged, data-heavy analytical workflows.

## Colors

The palette establishes an information-first dark theme built on deep indigo-slate neutrals, vibrant directional accents, and semantic segment thresholds:

- **Foundation Neutrals:**
  - Base Canvas (`#090D16`): The deepest level for backdrop isolation.
  - Surface Default (`#0F172A`): Primary card, panel, and dashboard container background.
  - Surface Raised (`#1E293B`): Elevated states, nested tables, tooltips, and flyouts.
  - Subtle Borders (`#334155` at 50–70% opacity): Precision boundary definition.
  - Text Hierarchy: Primary labels use `#F8FAFC`, secondary metrics use `#94A3B8`, and disabled/tertiary metadata uses `#64748B`.

- **Core & Semantic Accents:**
  - **Primary (`#6366F1` / `#4F46E5`):** Serves interactive elements, selected states, and core branding hooks.
  - **Champions & Loyalists (`#10B981` Emerald):** Identifies top-tier monetary output, high frequency, and healthy recency.
  - **At-Risk & Potential Churn (`#F59E0B` Amber):** Flags declining frequency or intermediate slippage requiring intervention.
  - **Churned & Lost (`#EF4444` Rose):** Alerts operators to expired lifecycles and immediate churn liabilities.
  - **Contextual Info (`#06B6D4` Cyan):** Used for neutral benchmark overlays and secondary segmentation cohorts.

## Typography

Typography prioritizes tabular alignment, rapid metric digestion, and high contrast against dark canvas tiers:

- **Headlines & KPI Values:** Rendered in **Plus Jakarta Sans** with negative tracking to convey solid, modern structure. Large metric totals use `metric-value` paired with tabular number figures (`font-variant-numeric: tabular-nums`) to prevent numeric jumping during real-time stream updates.
- **Body & Data Grid:** Rendered in **Inter** for neutral, utilitarian legibility in high-density tables and microcopy.
- **Case Rules:** Table column headers and segment status badges strictly utilize uppercase formatting with expanded letter-spacing (`code-sm` or `label-md`).

## Layout & Spacing

The layout utilizes a dynamic fluid grid engineered to balance high information density with systematic negative space:

- **Desktop (1280px+):** 12-column layout with `gutter-lg` (1.5rem) and `margin-lg` (2rem). KPI cards snap to 3-column spans (4 across) or 4-column spans (3 across). Detailed RFM scatter/treemap charts span 8 columns, while cohort breakdown panels anchor the adjacent 4 columns.
- **Tablet (768px – 1279px):** 8-column layout with `gutter` (1rem) and `margin-md` (1.5rem). Metric cards reflow to 2-column or 4-column blocks; heatmaps take full width.
- **Mobile (< 768px):** 4-column single-axis stack with `gutter` (1rem) and `margin` (1rem). Tables shift to horizontally scrollable viewports with frozen identifier columns.
- **Internal Density:** Components leverage the base 4px metric system (`space-xs` through `space-xl`). Data grid cells adhere to a compact 36px or 44px vertical height to preserve maximum viewport rows.

## Elevation & Depth

Visual hierarchy does not rely on heavy drop shadows, instead using subtle surface luminance tiering, low-contrast structural borders, and targeted luminescent accents:

- **Level 0 (App Shell / Canvas):** Neutral `#090D16`. Zero elevation.
- **Level 1 (KPI Cards, Tables, Standard Containers):** Surface neutral `#0F172A` wrapped in a crisp border (`1px solid rgba(51, 65, 85, 0.45)`). No blur shadows.
- **Level 2 (Active/Hover Cards, Segment Details):** Surface elevated `#1E293B`, border tinted slightly with primary indigo (`1px solid rgba(99, 102, 241, 0.3)`), paired with an ambient drop: `box-shadow: 0 4px 20px -2px rgba(0, 0, 0, 0.5)`.
- **Level 3 (Modals, Filter Drawers, Tooltips):** Surface `#1E293B` surrounded by `1px solid rgba(148, 163, 184, 0.2)` with a deep ambient shadow: `box-shadow: 0 12px 32px -4px rgba(0, 0, 0, 0.7)`.
- **Luminescence:** Active segment states leverage minimal, color-matched ambient glow (`0 0 12px rgba(99, 102, 241, 0.15)`) to direct focus without visually overpowering the data layer.

## Shapes

The shape vocabulary uses precision-machined geometry that balances technical structure with contemporary visual softness:

- **Default Radii (0.5rem / 8px):** Applied to standard interactive controls including text inputs, dropdown triggers, standard buttons, and inner card containers.
- **Expanded Radii (1rem / 16px):** Reserved exclusively for root-level dashboard modules, chart canvases, and modal dialogs.
- **Full Pill (`rounded-full`):** Strictly restricted to status tags, RFM segment chips (e.g., "Champions", "At Risk"), and quick-toggle state pills to cleanly contrast them against rigid data grids and linear graphs.

## Components

- **KPI Metric Cards:**
  Constructed on `#0F172A` with a 1px border (`#334155`). Top row houses the semantic metric name (`label-md`, `#94A3B8`) paired with an RFM axis badge (R, F, or M). The center displays the value using `metric-value` in `#F8FAFC`. The footer provides delta percentage tags styled with semantic emerald (`#10B981`) or rose red (`#EF4444`) pill indicators containing micro-trend sparklines.

- **Data Tables (RFM Customer Segments):**
  Headers use uppercase `code-sm` text on `#0F172A` with subtle bottom borders (`rgba(51, 65, 85, 0.6)`). Rows maintain a consistent 44px height with hover transitions to `#1E293B`. Numbers are aligned right using tabular figures. Customer recency scores (1–5), frequency counts, and monetary values are displayed alongside colored confidence bars.

- **Segment Status Chips:**
  Compact pill components with low-opacity chromatic fills and solid text:
  - *Champions:* Background `rgba(16, 185, 129, 0.12)`, text `#34D399`, border `rgba(16, 185, 129, 0.25)`.
  - *At Risk:* Background `rgba(245, 158, 11, 0.12)`, text `#FBBF24`, border `rgba(245, 158, 11, 0.25)`.
  - *Lost/Churn:* Background `rgba(239, 68, 68, 0.12)`, text `#F87171`, border `rgba(239, 68, 68, 0.25)`.
  - *Loyal/Active:* Background `rgba(99, 102, 241, 0.12)`, text `#818CF8`, border `rgba(99, 102, 241, 0.25)`.

- **Buttons & Interactive Controls:**
  - *Primary:* Solid `#4F46E5` background, hover to `#4338CA`, text `#FFFFFF`, subtle inset top highlight.
  - *Secondary / Outline:* Transparent fill, `1px solid #334155`, text `#F8FAFC`, hover background `#1E293B`.
  - *Ghost / Table Actions:* No border, `#94A3B8` icon/text, hover background `#1E293B` and `#F8FAFC` foreground.

- **Input Fields & Filter Selectors:**
  Background `#090D16` inset within `#0F172A` surfaces. Borders use `#334155`, transitioning to `#6366F1` with an outer glow on focus. Placeholder text in `#64748B`. Integrated segmented controls and range sliders (for Recency 1–5 scoring thresholds) leverage indigo-filled slider tracks with white thumb handles.

- **Chart & Matrix Containers:**
  Wraps RFM 5x5 grids, cohort heatmaps, and distribution plots. Uses `#0F172A` backgrounds with persistent inline header action controls (e.g., date ranges, cohort slice toggles, CSV exports). Axis gridlines must remain understated, set to `rgba(51, 65, 85, 0.3)`. Tooltips are pinned to Level 3 elevation with monospace coordinate indicators.