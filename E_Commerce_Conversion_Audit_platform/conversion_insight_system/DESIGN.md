---
name: Conversion Insight System
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
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2151da'
  primary: '#0037b0'
  on-primary: '#ffffff'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#004f35'
  on-tertiary: '#ffffff'
  tertiary-container: '#006948'
  on-tertiary-container: '#76eab6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-display:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers a rigorous, high-clarity enterprise environment engineered for technical e-commerce audits, conversion rate optimization (CRO), and funnel analytics. The design style combines modern corporate precision with disciplined data density, drawing directly from operational benchmarks like Stripe and Linear. 

The emotional tone balances institutional authority with rapid operational utility: clean, non-distracting, and hyper-legible. Visual noise is stripped back so complex conversion metrics, technical health scores, and critical drop-off alerts remain immediately scannable. The system instills confidence in executive stakeholders while providing tactical engineers and optimization leads with frictionless density, sharp boundaries, and clear hierarchy.

## Colors

The palette leverages a crisp, analytical hierarchy designed for long sessions and high information density.

- **Primary (`#1d4ed8`):** Royal Blue serves as the focused operational engine. It is strictly reserved for primary user actions, active navigation states, selected table rows, interactive links, and key focus rings.
- **Secondary (`#0f172a`):** Deep Slate/Charcoal establishes structural grounding. Used for top-tier headings, primary text, dark utility bars, and contrasting interactive icons.
- **Tertiary & Semantics:**
  - **Success / Healthy (`#059669`):** Reserved for conversion gains, optimal UX benchmark scores, passing tests, and positive trend lines. Paired with soft emerald tint containers (`#ecfdf5`).
  - **Warning (`#d97706`):** Highlights conversion risks, latency warnings, and sub-optimal audit heuristics.
  - **Critical / Danger (`#e11d48`):** Directs immediate visual focus toward funnel friction, critical drop-offs, and failing checkout stages. Paired with soft rose tint containers (`#fff1f2`).
- **Neutrals & Surfaces:**
  - Canvas: Base neutral starts at `#ffffff` for cards and modals, resting against an off-white `#f8fafc` (slate-50) canvas.
  - Borders & Dividers: Muted structural lines utilize `#e2e8f0` (slate-200) to partition sections cleanly without heavy visual weight.
  - Body & Secondary Copy: Ranges between `#334155` (slate-700) and `#64748b` (slate-500) to maintain crisp, accessible contrast ratios exceeding WCAG AAA standards.

## Typography

Typography relies on a single, systematic execution of Inter across all levels. Layouts achieve hierarchy through weight modulation (Regular 400, Medium 500, Semi-Bold 600) and strict tracking adjustments rather than expressive typefaces.

- **Headlines:** Set with negative letter-spacing to tighten optical spacing at scale, projecting an engineered, confident tone.
- **Labels & Micro-data:** Micro-copy (`label-sm`), including column headers, status tags, and audit category pills, uses uppercase treatment with expanded letter spacing (+0.04em) to maintain visual definition at 11px.
- **Tabular Data & Metrics:** For all numerical conversion statistics, currency, bounce rates, and latencies, activate tabular numerals (`font-feature-settings: 'tnum' 1, 'cv05' 1`) to ensure vertical alignment across dense auditing tables.

## Layout & Spacing

The layout model is built upon a 12-column responsive fluid grid anchored by strict maximum content bounds (1440px) to prevent data distortion on ultra-wide displays. 

- **Grid & Columns:**
  - **Desktop (1024px+):** 12 columns with 24px (`gutter`) separation and 32px (`margin`) outer edge offsets. Sidebars adhere to a standardized 240px or 280px fixed width, with primary dashboard grids reflowing organically.
  - **Tablet (768px - 1023px):** 8 columns with 16px (`gutter-sm`) separation and 24px edge offsets. Multi-metric audit cards reflow into 2-column pairs.
  - **Mobile (<768px):** 4 columns with 16px margins; panels stack linearly with horizontal scrolling allowed strictly for high-dimensional data tables.
- **Internal Spacing Cadence:**
  - Micro spaces (`space-xs`, `space-sm`) govern form controls, badge inner padding, and list item spacing.
  - Standard spaces (`space-md`, `space-lg`) handle card padding, table cell breathing room, and component stacks.
  - Section space (`space-xl`) isolates major audit modules (e.g., separating the Funnel Drop-off Visualizer from the Heuristic Scoring Matrix).

## Elevation & Depth

Depth is established primarily through crisp, 1px low-contrast outlines rather than heavy atmospheric projection, echoing the clarity of modern engineering dashboards.

- **Level 0 (Flat / Canvas):** Applied to the base canvas (`#f8fafc`). Non-elevated, structural dividing lines use `1px solid #e2e8f0`.
- **Level 1 (Card / Container):** Applied to primary metric cards, audit item modules, and table headers. Pure white surface (`#ffffff`) bounded by a subtle border (`1px solid #e2e8f0`) and an ambient, hairline shadow: `0 1px 2px 0 rgba(15, 23, 42, 0.04)`.
- **Level 2 (Dropdowns, Popovers, & Filter Flyouts):** Surfaces floating above active workflows. Bordered with `#cbd5e1`, paired with a structured shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals & Slide-over Audit Drawers):** Elevated overlays for deep dive diagnostics. Backed by a neutral tint backdrop (`rgba(15, 23, 42, 0.4)`), styled with `0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

## Shapes

The design system standardizes on `roundedness: 2`, delivering a calibrated corner radius of 0.5rem (8px) across core controls and 0.75rem to 1rem (12px to 16px) for larger containing blocks.

- **8px (`rounded-md`):** Default for interactive controls including text inputs, standard buttons, select menus, code snippets, and dropdown panels.
- **12px (`rounded-lg`):** Standard for audit cards, diagnostic metric clusters, workflow containers, and nested charts.
- **Full Radius (9999px):** Strictly constrained to contextual status indicators, metric delta badges, and presence dots.

## Components

- **Buttons:**
  - *Primary:* Solid `#1d4ed8` fill, white text, 8px border radius, subtle inner highlight (`box-shadow: inset 0 1px 0 rgba(255,255,255,0.15)`). Hover shifts to `#1e40af`.
  - *Secondary / Outline:* Crisp `#ffffff` surface, `#e2e8f0` border, `#0f172a` text. Hover introduces `#f8fafc` background.
  - *Ghost / Subdued:* Transparent surface, `#475569` text, providing clean utility within dense table headers.
- **Inputs & Form Controls:**
  - 36px standard height for data density. Crisp 1px border using `#cbd5e1`, shifting to `#1d4ed8` with a 2px offset ring on focus (`box-shadow: 0 0 0 3px rgba(29, 78, 216, 0.15)`). Monospace numerical values supported where inputs deal with exact revenue or conversion thresholds.
- **Data Cards:**
  - Built with `#ffffff` backgrounds, 12px corner radii, and a 1px solid `#e2e8f0` perimeter. Header zones demarcate audit categories with a 1px border-bottom; metric highlights sit alongside directional trend pills (+X% / -Y%).
- **Status Chips & Issue Badges:**
  - *Pass / Healthy:* `#ecfdf5` background, `#047857` label, 1px border in `#a7f3d0`.
  - *Critical Friction:* `#fff1f2` background, `#be123c` label, 1px border in `#fecdd3`.
  - *Audit Category Tags:* `#f1f5f9` background, `#475569` label, `#e2e8f0` border.
- **Audit Tables & Data Grids:**
  - Zero-margin cell layout with 40px row height for optimal scannability. Headers styled with `label-sm` in slate-500. Row hover triggers a subtle background shift to `#f8fafc`. Active or inspected audit items feature a 2px left border in `#1d4ed8`.
- **Conversion Funnel Bars:**
  - Stepped horizontal segment bars indicating stage-by-stage drop-off. Healthy progression rendered in `#1d4ed8`, with severe leakage points dynamically bordered or marked with a `#e11d48` indicator tag.