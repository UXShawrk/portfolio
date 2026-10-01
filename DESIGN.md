---
name: Aether Portfolio
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
  on-surface-variant: '#3f4850'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#00668a'
  on-secondary: '#ffffff'
  secondary-container: '#40c2fd'
  on-secondary-container: '#004d6a'
  tertiary: '#4e5e68'
  on-tertiary: '#ffffff'
  tertiary-container: '#667781'
  on-tertiary-container: '#fbfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#d3e5f1'
  tertiary-fixed-dim: '#b7c9d5'
  on-tertiary-fixed: '#0c1e26'
  on-tertiary-fixed-variant: '#384953'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
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
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-section: 6rem
---

## Brand & Style

This design system embodies an airy, modern, high-clarity portfolio aesthetic tailored for hybrid developer-designers. The identity balances precision engineering with delicate editorial taste. It avoids heavy, over-saturated accents in favor of a calm, sky-infused palette that places full focus on case studies, project metrics, and technical craft.

### Emotional Tone & Philosophy
- **Clarity & Light:** Expansive whitespace, subtle atmospheric shifts, and breathable compositions evoke calm competence.
- **Architectural Precision:** Every line, grid line, and layout boundary aligns to structural logic without feeling rigid or brutalist.
- **Understated Sophistication:** The interface steps back, allowing work samples, interactive demos, and written case studies to take center stage.

### Design Movement
**Refined Digital Minimalism with Atmospheric Micro-depth.** The visual language merges high-contrast neutral typography with ethereal ice-blue ambient surfaces, delicate low-contrast borders, and frosted translucent overlays.

## Colors

The palette is tuned around light mode with crisp tonal layering, evoking clarity and openness:

- **Primary (`#0284c7` / Tailwind `sky-600`):** The primary interaction anchor for primary actions, active navigational states, and focus rings. Strong enough to ensure WCAG AAA/AA compliance against crisp whites and pale tints.
- **Secondary (`#38bdf8` / Tailwind `sky-400`):** Used sparingly for micro-accents, glow states, interactive hover states, and live project badges.
- **Tertiary (`#e0f2fe` / Tailwind `sky-100`):** The ice-tinted surface foundation. Employed for chip backgrounds, subtle card fills, code block inline highlights, and decorative grid lines.
- **Neutral (`#0f172a` / Tailwind `slate-900`):** The grounding neutral tone for maximum typographic legibility. Supported by muted slate tones (`#475569` / `slate-600` for secondary body, `#94a3b8` / `slate-400` for tertiary/metadata).
- **Canvas Base (`#f8fafc` / Tailwind `slate-50` with pure `#ffffff` cards):** Ensures a subtle optical step between the ambient canvas and interactive card modules.

## Typography

Typography pairs **Plus Jakarta Sans** for body and display headers with **JetBrains Mono** for technical micro-copy, metadata, labels, and code snippets:

- **Display & Headlines:** Set in Plus Jakarta Sans with subtle negative tracking (`tracking-tight`) to create an editorial, high-end design presence.
- **Body:** Generous line heights ensure frictionless long-form reading on technical case studies and design rationale.
- **Labels & Tags:** JetBrains Mono injects developer authenticity into tech stack tags, commit dates, repository statistics, and category markers. Always set in uppercase with deliberate tracking (`tracking-wider`).

## Layout & Spacing

The portfolio employs a controlled 12-column responsive fluid grid constrained inside a maximum content width of `1200px` (`max-w-6xl` in Tailwind), guaranteeing that projects and typography maintain comfortable line lengths across ultrawide monitors.

### Breakpoints & Fluid Adaptation
- **Mobile (< 640px):** Single-column stack. Outer margins are `1.25rem` (`px-5`). Section gaps are compressed to `3rem` to maintain visual flow.
- **Tablet (640px – 1024px):** 6-column fluid grid. Outer margins are `2rem` (`px-8`). Two-up card arrangements for project showcases.
- **Desktop (1024px+):** 12-column grid with `2rem` gutters and `3rem` outer margins. Case study breakdowns leverage an asymmetrical 7:5 split (7 columns for visual showcase, 5 columns for project context, tech stack, and live links).

### Rhythmic Philosophy
Generous vertical spacing (`space-section` / `py-24`) creates breathing room between major showcase phases (Hero → Featured Works → Architecture & Labs → Writing → Colophon/Contact).

## Elevation & Depth

This design system avoids dark or heavy drop shadows, relying instead on **low-contrast outlines, frosted glass, and ambient ice-blue diffused tints**:

- **Ground Level (Canvas):** `bg-slate-50` provides a calm backdrop that eliminates harsh pure-white eye strain.
- **Surface Level (Cards & Containers):** Pure white (`bg-white`) paired with an ultra-fine border `border border-slate-200/80`.
- **Hover & Focus Elevation:** On hover, cards transition to a diffused ambient tint rather than deep darkness: `box-shadow: 0 12px 32px -4px rgba(2, 132, 199, 0.08), 0 4px 12px -2px rgba(15, 23, 42, 0.03)`.
- **Navigation & Floating Toolbars:** Fixed navigation bar uses glassmorphic frosted transparency: `backdrop-blur-md bg-white/80 border-b border-slate-200/60`.

## Shapes

The roundedness tier is set to **Level 2 (Rounded)**:

- **Standard Elements (Buttons, Inputs, Cards):** Built using `rounded-xl` (12px / `0.75rem`) to `rounded-2xl` (16px / `1rem`) for structural card boundaries.
- **Tags, Badges & Chips:** Full pill geometry (`rounded-full`) to contrast against rectangular project screenshots and architectural diagrams.
- **Code Elements:** Clean, restrained 8px radius (`rounded-lg`) matching developer terminal conventions.

## Components

### Buttons
- **Primary:** Solid Sky `bg-sky-600 hover:bg-sky-500 text-white font-medium text-sm px-5 py-2.5 rounded-xl transition-all duration-200 shadow-sm shadow-sky-600/20 active:scale-[0.98]`.
- **Secondary / Outline:** Transparent fill with structural framing `bg-white/80 hover:bg-sky-50/50 text-slate-700 hover:text-sky-700 border border-slate-200 hover:border-sky-300 font-medium text-sm px-5 py-2.5 rounded-xl transition-all duration-200`.
- **Icon / Ghost:** Neutral-to-primary minimal action `p-2 text-slate-500 hover:text-sky-600 hover:bg-sky-50 rounded-lg transition-colors`.

### Chips & Badges
- **Tech Stack Pill:** Monospace-driven, compact `bg-sky-50 text-sky-800 border border-sky-100/80 px-2.5 py-1 rounded-full text-xs font-mono tracking-tight inline-flex items-center gap-1.5`.
- **Status Indicator:** Pill shape featuring a pulsing status light `bg-emerald-50 text-emerald-700 border border-emerald-200/60 px-3 py-1 rounded-full text-xs font-medium inline-flex items-center gap-2`. Includes a `w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse`.

### Project Cards
- **Structure:** White core `bg-white rounded-2xl border border-slate-200/70 p-6 md:p-8 transition-all duration-300 hover:border-sky-300/80 hover:shadow-xl hover:shadow-sky-500/5 group`.
- **Media Preview:** Contained within `overflow-hidden rounded-xl bg-slate-100 border border-slate-150 aspect-[16/10]`. Subtle zoom on card hover `group-hover:scale-[1.02] transition-transform duration-500`.

### Form Fields & Inputs
- **Input / Textarea:** `bg-white border border-slate-200 text-slate-900 placeholder:text-slate-400 text-sm rounded-xl px-4 py-3 focus:outline-none focus:border-sky-500 focus:ring-4 focus:ring-sky-500/10 transition-all`.

### Interactive Code / Terminal Block
- **Container:** High-clarity developer sample card `bg-slate-900 text-slate-200 rounded-xl p-4 font-mono text-xs border border-slate-800 shadow-lg`.
- **Header:** Three subtle dot window controls with an ice-blue project path header (`text-sky-400`).