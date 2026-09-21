---
name: Rapid Response Clinical
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
  on-surface-variant: '#5c403c'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#916f6b'
  outline-variant: '#e6bdb8'
  surface-tint: '#bf0715'
  primary: '#b70011'
  on-primary: '#ffffff'
  primary-container: '#dc2626'
  on-primary-container: '#fff6f5'
  inverse-primary: '#ffb4ab'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006645'
  on-tertiary: '#ffffff'
  tertiary-container: '#008259'
  on-tertiary-container: '#e1ffec'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
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
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system operates under an **Urgent Clinical Modernism** ethos. It bridges mission-critical rapid response workflows with institutional healthcare dependability. Designed for hospital dispatchers, blood bank coordinators, lab techs, and on-call clinicians, the visual interface must prioritize instant cognitive clarity, zero-friction decision making, and clinical authority.

### Personality & Tone
- **Authoritative & Trustworthy:** Unyielding precision, crisp information architecture, and rigorous hierarchy to prevent operational errors.
- **Urgent without Panic:** Signal-driven prioritization that guides the eye directly to acute shortages and critical logistics without inducing sensory fatigue.
- **Clinical & Modern:** High cleanliness, generous contrast, structural containment, and subtle tactile grounding.

### Visual Style
A hybrid of **Modern Corporate SaaS** and **Clinical Precision Instrument**:
- Razor-sharp data density balanced by disciplined white space.
- Subtle containment lines (`border-slate-200`) paired with structured cards.
- Highly visible status signifiers ensuring instantaneous scanning across ambient light conditions (e.g., triage centers, dimly lit operating rooms, or brightly lit dispatch desks).

## Colors

The palette leverages a high-contrast functional color matrix where color is never merely decorative; every hue communicates operational status, severity, or clinical workflow role.

### Palette Architecture
- **Primary / Emergency Crimson (`#DC2626`):** Reserved strictly for critical shortages, expired/expiring stock thresholds, emergency dispatch triggers, and acute calls to action. A secondary rose-red (`#E11D48`) is reserved for platelet-specific alerts or sub-tier urgent badges.
- **Secondary / Deep Slate Navy (`#0F172A` & `#1E293B`):** Anchors core infrastructure—global navigation, app shells, high-priority typography, and commanding metric surfaces. Provides depth and institutional gravitas.
- **Tertiary / Clinical Emerald (`#10B981`):** Signifies verified inventory, ready-for-transfusion units, matched donors, and fulfilled logistics.
- **Urgency Warning Amber (`#F59E0B`):** Denotes impending shortages, cross-match testing in progress, and non-immediate transit buffers.
- **Informational / Sky & Indigo (`#0284C7` / `#4F46E5`):** Denotes cold-chain sensor telemetry, regular logistical routing, and system metadata.
- **Neutral Canvas (`#FFFFFF`, `#F8FAFC`, `#F1F5F9`):** Pristine clinical whites and cool slate neutrals provide a clean, hospital-grade background that prevents eye fatigue during 12-hour shifts.

### Contrast & Accessibility
All interactive text against colored containers maintains at minimum WCAG 2.1 AA (4.5:1), with primary data metrics achieving AAA (7:1+) standards against background fields.

## Typography

The type system blends the structural, ergonomic clarity of **Plus Jakarta Sans** for headlines and operational metrics with the neutral, hyper-legible utility of **Inter** for clinical tables, logs, donor charts, and system alerts.

### Typographic Principles
- **Numerical Dominance:** Tabular figures are enforced across all metric cards, inventory counts, blood unit counters, and ETA readouts to ensure vertical alignment in high-density tables.
- **Hierarchy Under Stress:** Status badges and blood group identifiers (e.g., `O-NEG`, `AB+`, `PLT- apheresis`) utilize `label-sm` with slight uppercase tracking (`0.04em`) to ensure instant recognition even on smaller or low-resolution hospital monitors.
- **Line Height Optimization:** Tightened line heights for headlines avoid vertical sprawl, while body text retains standard line heights for unstrained legibility over long shifts.

## Layout & Spacing

A disciplined 8pt-based fluid grid designed to support dense, real-time clinical monitoring alongside responsive emergency field views.

### Grid & Structure
- **Desktop (1280px+):** 12-column layout with 24px (`1.5rem`) gutters and a fixed 260px tactical sidebar navigation. Central workspace hosts dual- or triple-pane operational splits (e.g., Live Requests pane, Inventory Level Matrix, and Transit Tracking Map).
- **Tablet (768px – 1024px):** 8-column layout with 20px (`1.25rem`) gutters. The sidebar collapses to an icon rail, and multi-pane views stack into tabbed operational workflows.
- **Mobile (320px – 767px):** 4-column layout with 16px (`1rem`) gutters and zero-padding card bleeds on rapid-action drawers to maximize viewable chart area for emergency mobile units.

### Spacing Rhythm
- Compact internal component padding (`space-xs` to `space-sm`) maintains data density in unit allocation matrices and donor lists.
- Boundary containers and sectional divisions rely on `space-lg` and `space-xl` to ensure cognitive separation between distinct emergency tiers.

## Elevation & Depth

To preserve clinical focus, elevation avoids exaggerated skeuomorphic drop shadows. Instead, the interface relies on **tonal layered containment** paired with **crisp low-contrast outlines** and subtle, diffused ambient occlusion.

### Surface Tiers
- **Base Canvas (`#F8FAFC`):** The foundational clinical neutral workspace.
- **Card Tier 1 (`#FFFFFF`):** Base analytical cards, data tables, and resting modules. Contained by a crisp `1px border-slate-200` (`#E2E8F0`) edge.
- **Card Tier 2 / Elevated Floating Panes:** Modals, active search filters, and popover route confirmations. Elevated with a fine outline (`border-slate-200`) and an ambient shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Emergency Alert Elevation:** Acute emergency action drawers and critical blood callouts break standard elevation using an emergency accent ring: `box-shadow: 0 0 0 1px #DC2626, 0 10px 15px -3px rgba(220, 38, 38, 0.12)`.

## Shapes

The design system incorporates **Level 2 (Rounded)** curvature tailored to a modern SaaS dashboard:
- Base cards, data containers, and modal dialogs adopt an authoritative `rounded-xl` (16px / `1rem`), softening clinical severity without sacrificing structural discipline.
- Interactive components such as buttons, dropdowns, search inputs, and filter toggles apply a clean `rounded-lg` (8px / `0.5rem`).
- Real-time inventory pill counters, blood-type identifiers, and role-based validation badges utilize fully rounded pill caps (`rounded-full`) for instant tactile differentiation from structural cards.

## Components

### Buttons
- **Primary Emergency:** Solid `#DC2626` background, white text, 8px corner radius, bold weight. Used exclusively for operations like "Initiate STAT Dispatch", "Issue Code Red Callout", or "Confirm Transfusion".
- **Primary Routine / Action:** Slate Navy (`#0F172A`) or Clinical Indigo (`#4F46E5`) for standard actions such as "Log Inventory Entry", "Export Manifest", or "Filter Registry".
- **Secondary / Outline:** White background with a `1px border-slate-200` edge, slate-700 text, and a slight slate-50 hover fill.
- **Destructive Subtle:** Soft red wash (`#FEF2F2`) with `#B91C1C` text for cancelling requests or unlinking units.

### Status Chips & Clinical Badges
- **Blood Group Badge:** High-contrast pill container. Black/navy outline with bold blood group identification (e.g., `O-`, `A+`, `Platelets Single-Donor Apheresis`).
- **Emergency Role Chips:** 
  - `STAT Emergency`: Bright crimson background (`#FEE2E2`), crimson text (`#991B1B`), leading pulse dot indicator.
  - `Verified / Available`: Emerald background (`#ECFDF5`), deep emerald text (`#065F46`), checkmark prefix.
  - `Critical Threshold / Depleted`: Amber background (`#FEF3C7`), dark amber text (`#92400E`), warning hazard icon.
  - `In-Transit / Cold-Chain Active`: Sky blue background (`#E0F2FE`), deep blue text (`#075985`), telemetry signal icon.

### Form Inputs & Selectors
- **Input Fields:** Crisp `#FFFFFF` surface, `1px solid #CBD5E1` border, 8px radius. Active focus transitions to a primary red or slate halo (`ring-2 ring-slate-900/10 border-slate-900`).
- **Validation & Units:** Inputs featuring blood volume (mL), unit counts, and donor pin codes feature fixed unit suffixes and high-visibility error labels placed strictly below the field.

### Data Tables & Inventory Lists
- Compact row height (48px) with subtle bottom borders (`#F1F5F9`). Alternating hover state (`#F8FAFC`).
- Pinned header with uppercase slate-500 labels in `label-sm`.
- Embedded live countdown timers for perishable platelets (5-day lifespan tracker) with automatic amber/red tint transitions.

### Cards & Metrics
- **Inventory Metric Card:** White surface, `1px border-slate-200`, `rounded-xl` radius. Upper bar features blood type badge and quick stock ratio (e.g., "14 Units | +4 Reserved"). Lower segment contains miniature vector bar showing cold storage capacity thresholds.