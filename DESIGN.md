---
name: Trace Desk AML Workspace
description: A disciplined investigation workspace that keeps public-chain evidence, analyst reasoning, and QC review visibly distinct.
colors:
  ink: "#13212b"
  muted: "#5b6b77"
  soft: "#eef2f4"
  line: "#d6dee3"
  paper: "#f7f9fa"
  white: "#fff"
  navy: "#0d1d28"
  navy-2: "#142c3a"
  teal: "#087c75"
  teal-dark: "#075e59"
  teal-soft: "#dff2ef"
  amber: "#a45c08"
  amber-soft: "#fff3dd"
  red: "#9a2f2f"
  navy-ink: "#122a36"
  navy-rule: "#27414f"
  navy-rule-raised: "#28414f"
  field-label: "#293b46"
  graph-outline: "#332c59"
  status-ink: "#344b58"
  support-ink: "#40545f"
  filter-ink: "#405660"
  table-ink: "#41545f"
  graph-label: "#415864"
  hero-copy: "#465966"
  brand-rule: "#5a7d89"
  warning-ink: "#5b3b13"
  arrow: "#607986"
  context-label: "#657984"
  indirect-node: "#665a9b"
  secondary-rule: "#6f8794"
  warning-button-ink: "#714006"
  graph-edge: "#78909c"
  shell-accent: "#7fd4cb"
  warning-hover: "#8a4d06"
  evidence-link: "#98ddd5"
  control-rule: "#9eacb5"
  shell-muted: "#9eb1bb"
  sequence-rule: "#9fb2bb"
  brand-accent: "#a5e3dc"
  table-action-rule: "#a8b7bf"
  input-rule: "#aebbc3"
  reviewer-rule: "#b7c5cb"
  expectation-rule: "#b9d2cf"
  casebar-rule: "#bfd6d2"
  success-rule: "#bfe5df"
  warning-rule: "#c48228"
  workflow-copy: "#cbd8dd"
  subject-node: "#cc8b20"
  topbar-link: "#d8e4e8"
  evidence-copy: "#dbe6ea"
  topbar-copy: "#dfe9ed"
  warning-border: "#e1bd87"
  checklist-rule: "#e5eaed"
  record-rule: "#e8edef"
  table-head: "#e8eef1"
  secondary-fill: "#edf3f5"
  casebar-fill: "#edf5f4"
  reviewer-fill: "#f1f5f6"
  row-hover: "#f4f8f8"
  graph-paper: "#f8fafb"
typography:
  display:
    fontFamily: "Public Sans, Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(42px, 5vw, 70px)"
    fontWeight: 760
    lineHeight: 1.02
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Public Sans, Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(24px, 2.2vw, 34px)"
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Public Sans, Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.25
  body:
    fontFamily: "Public Sans, Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  body-large:
    fontFamily: "Public Sans, Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Public Sans, Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 800
    lineHeight: 1.5
    letterSpacing: "0.08em"
  mono:
    fontFamily: "ui-monospace, SFMono-Regular, Consolas, monospace"
    fontSize: "0.92em"
    fontWeight: 400
    lineHeight: 1.5
  micro:
    fontSize: "11px"
  compact-label:
    fontSize: "13px"
  compact-body:
    fontSize: "14px"
  mobile-body-large:
    fontSize: "17px"
  panel-title:
    fontSize: "18px"
  scope-title:
    fontSize: "20px"
  mobile-display:
    fontSize: "40px"
rounded:
  square: "0"
  xs: "2px"
  sm: "3px"
  md: "4px"
  round: "50%"
spacing:
  xs: "4px"
  sm: "8px"
  control: "10px"
  md: "14px"
  field: "16px"
  section: "24px"
  panel: "28px"
  major: "32px"
  shell: "64px"
components:
  button-primary:
    backgroundColor: "{colors.teal-dark}"
    textColor: "{colors.white}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "9px 15px"
    height: "42px"
  button-secondary:
    backgroundColor: "{colors.soft}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "9px 15px"
    height: "42px"
  button-warning:
    backgroundColor: "{colors.amber-soft}"
    textColor: "{colors.amber}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "9px 15px"
    height: "42px"
  field:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: "11px 12px"
    height: "44px"
  workspace-section:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.square}"
    padding: "clamp(22px, 3vw, 38px)"
  source-label:
    textColor: "{colors.teal-dark}"
    typography: "{typography.label}"
---

# Design System: Trace Desk AML Workspace

## Overview

**Creative North Star: "The Disciplined Investigation File"**

Trace Desk is an evidence-led enterprise workspace, not a promotional crypto dashboard. A graphite and navy application shell holds a light slate work surface where scope, evidence, interpretation, and limitations remain visibly distinct. The system is compact, sober, and operational: it should feel credible to an AML analyst, legible to a QC reviewer, and understandable to a recruiter exploring the saved case.

The visual system uses square-edged white work areas, quiet rules, tabular numerals, and one teal interaction color. Amber is reserved for limitations and attention; red is reserved for actionable errors. Decoration never competes with case state or evidence.

**Key Characteristics:**

- Dark institutional shell over a light, high-legibility case surface.
- One teal interaction voice and one amber limitation voice.
- Compact square components with explicit state, scope, and provenance.
- Evidence-first layouts that pair actions with the information they affect.
- Honest prototype language that never implies production controls.

## Colors

The palette separates shell, work surface, interaction, limitation, and error roles without decorative gradients.

### Primary

- **Investigation Teal** (`#087c75`): active links, graph relationships, hover states, and confirmed interaction state.
- **Deep Investigation Teal** (`#075e59`): primary buttons and high-contrast interactive text on light surfaces.
- **Evidence Wash** (`#dff2ef`): selected, hover, and case-context surfaces.

### Secondary

- **Institutional Navy** (`#0d1d28`): top bar and evidence-detail surface.
- **Raised Navy** (`#142c3a`): dark-shell hover and active states.

### Tertiary

- **Limitation Amber** (`#a45c08`): warnings and attention text only.
- **Limitation Paper** (`#fff3dd`): prototype and investigative-limit backgrounds.
- **Action Error** (`#9a2f2f`): actionable validation and QC errors.

### Neutral

- **Evidence Ink** (`#13212b`): primary text and field content.
- **Review Gray** (`#5b6b77`): secondary explanation and metadata.
- **Slate Wash** (`#eef2f4`): grouped controls, submission summaries, and technical detail surfaces.
- **Case Rule** (`#d6dee3`): borders, table rules, and structural separation.
- **Work Paper** (`#f7f9fa`): page background.
- **Document White** (`#fff`): panels, fields, and evidence records.

**The Semantic Accent Rule.** Teal means interaction or confirmed state. Amber means limitation or attention. Red means an actionable error. Do not use these colors decoratively.

## Typography

**Display Font:** Public Sans with Aptos, Segoe UI, Roboto, Helvetica, Arial, sans-serif fallbacks  
**Body Font:** Public Sans with the same system fallbacks  
**Label/Mono Font:** ui-monospace with SFMono-Regular, Consolas, monospace fallbacks

**Character:** Public Sans gives the workspace a clear, institutional voice without feeling like a generic product template. Monospace is limited to addresses, hashes, block ranges, token units, and other evidence whose character sequence matters.

### Hierarchy

- **Display** (760, `clamp(42px, 5vw, 70px)`, 1.02): the single page proposition; maximum tracking is `-0.035em`.
- **Headline** (700, `clamp(24px, 2.2vw, 34px)`, 1.12): stage and major workspace headings.
- **Title** (700, `22px`, 1.25): compact panel, scope, and workbench headings.
- **Body Large** (400, `19px`, 1.65): hero explanation, constrained to a readable measure.
- **Body** (400, `16px`, 1.5): instructions, findings, and form support copy.
- **Label** (800, `12px`, `0.08em`, uppercase): source state, field-state labels, and table headers; never used as a decorative kicker.
- **Mono** (400, `0.92em`, 1.5): hashes, addresses, block identifiers, and raw evidence only.

**The Evidence Type Rule.** Monospace signals literal evidence, never generic technical sophistication.

## Layout

The application uses a maximum `1540px` shell with responsive side padding from `20px` to `64px`. The first view is a two-column hero: product purpose on the left and a unified case-start panel on the right. The investigation then follows a four-stage workflow rail, a persistent case bar, a metric strip, and focused work areas.

Desktop workbenches use asymmetric grids so primary evidence or narrative work receives more space than scope, detail, or checklist rails. Evidence and assessment layouts keep contextual information beside the action it supports. Section padding is `clamp(22px, 3vw, 38px)` with `18px` vertical separation between work areas.

At `1050px`, the hero and all multi-rail workbenches collapse to one column; context rails move below the primary work. At `720px`, the shell uses `14px` side padding, workflow navigation becomes horizontally scrollable, metrics become a 2×2 grid, case context scrolls horizontally, and evidence tables become labeled stacked records. Primary actions remain at least 42–44px high and mobile decisions stack vertically.

## Elevation & Depth

The system is flat by default. Depth comes from tonal contrast, borders, sticky positioning, and one soft shadow beneath the persistent case bar (`0 10px 20px rgba(13,29,40,.06)`). White work areas do not float on ornamental shadows. The dark evidence-detail surface creates functional contrast for selected transaction detail.

**The Flat-by-Default Rule.** A surface earns elevation only when it must remain contextually above scrolling evidence.

## Shapes

Trace Desk uses restrained, nearly square geometry. Work areas and navigation are square. Buttons use `4px` corners, fields use `3px`, compact table actions use `3px`, and graph categories use shape only where it creates a redundant accessibility cue. Circular geometry is reserved for subject or indirect graph nodes; direct counterparties use a square marker.

Borders are one pixel and structural. Do not add thick side accents, ornamental capsules, or rounded card walls. Form controls stay dense but never fall below the implemented 42–44px action height.

## Components

### Buttons

- **Shape:** restrained rectangle (`4px`) with `9px 15px` padding and a minimum height of `42px`.
- **Primary:** deep teal background, white text, and one primary action per stage.
- **Secondary:** slate background with ink text and a visible gray border.
- **Quiet:** transparent or white; used for reset, export, and supporting actions.
- **Warning:** amber paper with a darker amber border and text; used for return-for-correction and limitation-sensitive actions.
- **Hover / Focus:** teal-soft hover for neutral buttons; primary shifts from deep teal to teal. Every interactive element uses a 3px translucent teal focus outline with a 2px offset.

### Chips

- **Style:** compact source and role labels use uppercase 12px label type without decorative pill backgrounds.
- **State:** state is communicated through wording and semantic color, never color alone.

### Cards / Containers

- **Corner Style:** square work sections; no card-wall treatment.
- **Background:** document white over work paper; grouped subregions use slate wash.
- **Shadow Strategy:** flat by default; only the sticky case bar receives a soft context shadow.
- **Border:** 1px case rule.
- **Internal Padding:** `clamp(22px, 3vw, 38px)` for major work areas; 12–24px for compact evidence and review regions.

### Inputs / Fields

- **Style:** white field, 1px gray border, 3px corners, `11px 12px` padding, and a 44px minimum height.
- **Focus:** translucent teal outline plus teal border.
- **Error / Disabled:** errors use red text near the relevant action; disabled controls reduce opacity and use a not-allowed cursor.

### Navigation

The navy workflow rail exposes Collect, Explore, Assess, and QC review as four equal stages. Teal numerals reinforce order. The rail remains sticky and becomes horizontally scrollable on mobile. The persistent case bar beneath it keeps source, subject, scope, QC state, file state, and Save visible without implying server persistence.

### Evidence Workbench

Graph, relationship list, filter state, evidence table, and selected transaction detail are one system. Graph meaning is redundant in color, shape, text legend, and relationship list. Filtering always produces a text status. On mobile, each table row becomes a labeled evidence record.

### QC Workbench

QC presents a readable submitted-snapshot summary before optional technical JSON. A visible prototype limitation explains that identity, permissions, separation of duties, and a tamperproof audit trail are not enforced. Analyst and reviewer areas are visually distinct but never presented as authenticated roles.

## Do's and Don'ts

### Do:

- **Do** keep scope, evidence, interpretation, and limitations visually distinct.
- **Do** keep current case source, subject, QC state, and portable-file state visible.
- **Do** pair every evidence filter with a readable status and clear action.
- **Do** reserve teal, amber, and red for their documented semantic roles.
- **Do** preserve keyboard focus, reduced-motion behavior, text alternatives, table captions, and mobile evidence labels.
- **Do** state file-based persistence and prototype control limits at the action they affect.

### Don't:

- **Don't** add gradients, glows, dotted technical textures, glass effects, or decorative status pills.
- **Don't** imply autosave, authenticated reviewers, enforced separation of duties, wallet attribution, or automated compliance decisions.
- **Don't** use color as the only graph or status cue.
- **Don't** use rounded cards as the default page structure or nest cards inside cards.
- **Don't** use monospace for ordinary headings, labels, or body copy.
- **Don't** hide technical limits inside a footer or separate documentation page.
