---
name: Clarity Flow
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
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4c'
  on-tertiary-container: '#7df1bd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.025em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system delivers an approachable, focus-driven productivity experience designed for students and novice coders. It blends clean modern utility with soft, tactile ergonomics to dismantle the cognitive friction often associated with task management.

### Personality & Demeanor
- **Encouraging & Uncluttered:** Prioritizes breathing room, zero visual noise, and immediate task clarity.
- **Modern & Reassuring:** Uses crisp indigo tones and friendly rounded geometries to evoke dependable structure without feeling rigid or corporate.
- **Tactile & Responsive:** High-contrast tap zones and smooth micro-elevations instill confidence in every gesture.

### Visual Architecture
The visual style draws from contemporary mobile-first product design, pairing crisp white modular cards (`#FFFFFF`) against an airy, anti-glare canvas (`slate-50`). Low-contrast surface borders combined with ultra-diffused drop shadows establish tangible layers that feel native on touch devices and centered desktop viewpoints.

## Colors

The palette establishes an intentional hierarchy focused on high legibility, color-coded task categorization, and low cognitive fatigue.

### Core Color Roles
- **Primary (`#4F46E5` / Indigo-600):** Governs primary calls-to-action, floating action buttons, focused states, and checked indicators. Communicates focus and intention.
- **Secondary (`#0284C7` / Sky-600):** Applied across analytical accents and academic/study context badges.
- **Tertiary (`#059669` / Emerald-600):** Represents life, health, completion, and personal tasks.
- **Neutral Primary (`#0F172A` / Slate-900):** Anchors headlines, primary item titles, and high-emphasis interface text.

### Functional Surfaces & Categorical Badges
- **Canvas Base:** `#F8FAFC` (Slate-50) creates an anti-fatigue workspace backdrop.
- **Elevated Surfaces:** `#FFFFFF` (Pure White) defines floating cards, sheets, and active filter states.
- **Dividers & Outlines:** `#E2E8F0` (Slate-200) sets structural boundaries without harsh contrast.
- **Muted Elements & Hints:** `#64748B` (Slate-500) for timestamps, secondary subtitles, and placeholders.
- **Category Badge – Study (공부):** Background `#E0F2FE` (Sky-100), Foreground `#0369A1` (Sky-700).
- **Category Badge – Personal (개인):** Background `#D1FAE5` (Emerald-100), Foreground `#047857` (Emerald-700).
- **Category Badge – Other (기타):** Background `#F3E8FF` (Purple-100), Foreground `#7E22CE` (Purple-700).
- **Destructive:** Background `#FEE2E2` (Red-100), Foreground `#DC2626` (Red-600).

## Typography

Inter handles all typographic requirements, delivering consistent metrics across Latin characters and Korean glyphs (via system font fallback to Pretendard/Apple SD Gothic Neo).

### Implementation Rules
- **Headline Hierarchy:** Keep screen titles to `headline-xl` (e.g., date headers or app titles) and card group headers to `headline-sm`.
- **Readability on Mobile:** Standard todo item titles use `body-lg` with a medium weight (`500`) to guarantee instant legibility on small displays. Completed items retain `body-lg` while switching to `#94A3B8` (Slate-400) and applying a strike-through decoration.
- **Labels & Tags:** Category tags, counts, and metadata rely strictly on `label-md` with semi-bold weights for rapid contextual scanning.

## Layout & Spacing

The layout is built around a mobile-first paradigm optimized for single-thumb navigation while maintaining a centered, contained presentation on larger devices.

### Screen Layout & Centering
- **Mobile (< 640px):** Spans full viewport width with `1rem` horizontal screen edge margins (`margin`). Internal component vertical gap adheres to `0.75rem` (`space-md`).
- **Tablet & Desktop (≥ 640px):** Constrained to a centered container (`max-width: 28rem` / `448px`, matching Tailwind `max-w-md`). The background outside this frame retains a subtle Slate-100 tone to keep attention focused on the app card.

### Touch Targets
- All primary interactive elements (buttons, filter chips, checkboxes, icon triggers) must enforce a minimum interactive boundary of **44px × 44px**, even if the visible element itself is more compact.

## Elevation & Depth

This system uses soft ambient shadows paired with low-contrast structural borders to define elevation without visual clutter.

### Elevation Levels
- **Base Level (Canvas):** Flat `#F8FAFC` without shadow.
- **Level 1 (Cards & Todo Items):** `#FFFFFF` fill with border `1px solid #E2E8F0` and shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Active/Hovered Cards & Dropdowns):** `#FFFFFF` fill with shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Floating Action Button & Sheet Overlays):** Indigo FAB carries a primary-tinted ambient drop shadow: `0 10px 15px -3px rgba(79, 70, 229, 0.3), 0 4px 6px -4px rgba(79, 70, 229, 0.2)`. Modals use `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.05)`.
- **Backdrop Scrim:** Modal curtains utilize `rgba(15, 23, 42, 0.4)` with an optional backdrop blur of `4px`.

## Shapes

The interface uses soft, approachable rounded corners to reinforce its welcoming feel.

### Border Radius Rules
- **Task Cards & Modals:** Standardized on `rounded-2xl` (`1rem` / `16px`) to produce gentle, tactile modules.
- **Action Buttons & Form Inputs:** Set to `rounded-xl` (`0.75rem` / `12px`) for balanced button shapes.
- **Pill Badges & Filter Tabs:** Set to `rounded-full` (`9999px`) to emphasize selectable, pill-like shapes.
- **Checkboxes:** Styled with `rounded-lg` (`0.5rem` / `8px`) to differentiate them from circular radio buttons while avoiding sharp right angles.

## Components

### Buttons
- **Primary Button:** Height 48px, background `#4F46E5`, text `#FFFFFF`, font `label-lg`, radius `12px`. Hover state `#4338CA`. Active state scales to `0.98`.
- **Secondary Button:** Height 48px, background `#F1F5F9`, text `#334155`, font `label-lg`, radius `12px`. Hover state `#E2E8F0`.
- **Floating Action Button (FAB):** 56px × 56px circle (`rounded-full`), positioned fixed at bottom-right of the `max-w-md` container (`bottom: 1.5rem`, `right: 1.5rem`). Filled with `#4F46E5` and holding a crisp white `+` icon (24px).

### Filter Chips (전체, 진행 중, 완료)
- Displayed horizontally in an edge-to-edge scrollable segment with `0.5rem` gaps.
- **Active State:** Background `#4F46E5`, text `#FFFFFF`, shadow-sm, radius `9999px`.
- **Inactive State:** Background `#FFFFFF`, text `#64748B`, border `1px solid #E2E8F0`, radius `9999px`. Padding `0.5rem 1rem`.

### Category Badges
- Compact pills (`rounded-full`, height 24px, padding `0.25rem 0.625rem`, font `label-md`).
- **공부 (Study):** Background `#E0F2FE`, Text `#0369A1`.
- **개인 (Personal):** Background `#D1FAE5`, Text `#047857`.
- **기타 (Other):** Background `#F3E8FF`, Text `#7E22CE`.

### Task Items (Todo Card)
- **Container:** Background `#FFFFFF`, radius `16px`, padding `1rem`, border `1px solid #E2E8F0`, shadow-sm.
- **Layout:** Flex row with `gap: 0.75rem`. Left contains the checkbox; center houses the category badge, item title (`body-lg`), and due date/time (`body-sm`, `#64748B`); right contains edit and delete action buttons.
- **Completed State:** Item title turns `#94A3B8` with `line-through`. Card opacity eases to `0.75`.

### Checkbox
- Dimensions: 24px × 24px embedded in a 44px tap target zone. Radius `8px`.
- **Unchecked:** Border `2px solid #CBD5E1`, background `#FFFFFF`.
- **Checked:** Border `2px solid #4F46E5`, background `#4F46E5`, housing a white centered checkmark glyph.

### Form Inputs
- Height 48px, border `1.5px solid #CBD5E1`, background `#FFFFFF`, radius `12px`, padding horizontal `1rem`, text `body-md` (`#0F172A`).
- **Focus:** Border color transitions to `#4F46E5` with an outer ring `3px rgba(79, 70, 229, 0.15)`. Outline is disabled.

### Modals & Bottom Sheets
- On mobile, creation dialogs slide upward as a bottom sheet (`rounded-t-2xl`, background `#FFFFFF`, padding `1.5rem`).
- On desktop container mode, transitions into a centered dialog box (`rounded-2xl`, max width `90%`, padded `1.5rem`).