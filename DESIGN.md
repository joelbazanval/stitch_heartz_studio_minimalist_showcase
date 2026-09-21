---
name: Editorial Obsidian
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#444748'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#9b4422'
  on-secondary: '#ffffff'
  secondary-container: '#fe9168'
  on-secondary-container: '#752907'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#201b14'
  on-tertiary-container: '#8b8379'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59b'
  on-secondary-fixed: '#380d00'
  on-secondary-fixed-variant: '#7c2e0c'
  tertiary-fixed: '#ebe1d6'
  tertiary-fixed-dim: '#cfc5ba'
  on-tertiary-fixed: '#201b14'
  on-tertiary-fixed-variant: '#4c463e'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display:
    fontFamily: Cormorant Garamond
    fontSize: 5.5rem
    fontWeight: '600'
    lineHeight: '1.08'
    letterSpacing: 0em
  display-mobile:
    fontFamily: Cormorant Garamond
    fontSize: 3.25rem
    fontWeight: '600'
    lineHeight: '1.12'
    letterSpacing: 0em
  headline-lg:
    fontFamily: Cormorant Garamond
    fontSize: 3.75rem
    fontWeight: '600'
    lineHeight: '1.14'
    letterSpacing: 0em
  headline-lg-mobile:
    fontFamily: Cormorant Garamond
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: '1.18'
    letterSpacing: 0em
  headline-md:
    fontFamily: Cormorant Garamond
    fontSize: 2.375rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0em
  headline-sm:
    fontFamily: Cormorant Garamond
    fontSize: 1.625rem
    fontWeight: '500'
    lineHeight: '1.45'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.65'
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Jost
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.09em
  label-md:
    fontFamily: Jost
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0.12em
  label-sm:
    fontFamily: Jost
    fontSize: 0.6875rem
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0.14em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style
The design system embodies a modern editorial, museum-grade production house sensibility. It caters to high-caliber brand partners, luxury clients, and creative directors seeking cinematic execution. 

The aesthetic is grounded in architectural minimalism paired with haute editorial print traditions. It evokes restraint, deliberate composition, and quiet authority. Surfaces feel tactile and paper-like rather than digital, utilizing expansive negative space, razor-sharp hairline dividers, disciplined index markers (e.g., `01`, `02`, `03`), and high-impact typographic juxtaposition.

## Colors
The palette balances warm bone substrate with dense obsidian solids and disciplined mineral accents:

- **Canvas & Backing (`#FAF8F5`)**: The foundation is a warm alabaster/bone tone, eliminating clinical white in favor of archival print stock warmth.
- **Deep Obsidian (`#121212`)**: Primary text, authoritative borders, and monolithic button states use an absolute deep charcoal tone.
- **Terracotta Sienese (`#C2623D`)**: An evocative, warm earth accent reserved strictly for micro-focal elements, live badges, active index callouts, and audio state monitors.
- **Warm Sand & Zinc (`#D9CFC4`, `#E8E3DC`, `#E2DDD6`)**: Used for hairline grid lines, structural rules, and neutral secondary surfaces that build architectural depth without heavy shadows.

## Typography
Typographic rhythm relies on the tension between three distinct type personalities:

1. **Cormorant Garamond**: High-contrast Garamond serif used for the display scale — major titles, section identifiers and key statements. Refined, literary and quietly luxurious; always set with neutral tracking (`0em`) and generous leading so its fine strokes breathe.
2. **Inter**: Neutral, near-invisible grotesque reserved for narrative descriptions, credits, case studies and interface copy. Optimised for calm, unhurried reading at small sizes.
3. **Jost**: Geometric, Futura-inspired sans acting as the metadata layer for numbered sequences (`01`, `02`), runtimes, framing tags, category indexes, buttons and navigation.

Maintain uppercase formatting with wide tracking (`0.09em` - `0.14em`) for all `label-*` tags to anchor the measured, architectural rhythm. Never tighten the serif display scale below `0em`.

## Layout & Spacing
The layout follows a 12-column architectural grid inspired by broadsheet editorial design.

- **Margins**: Mobile uses `1.5rem` outer margins. Desktop expands to `4rem` (or dynamic padding bounded to a `1600px` max canvas).
- **Rhythm**: Sections require dramatic pacing; breathing space between case studies and media reels should default to `space-xl` or larger programmatic gaps (`6rem` to `10rem`).
- **Dividers**: Columns and rows should be structured using visible 1px hairline rules (`#E2DDD6`) rather than elevation surfaces.

## Elevation & Depth
Elevation is rendered entirely without skeuomorphic dropshadows or heavy blurs. The system relies strictly on **low-contrast outlines, hairline framing, and planar tonal layering**:

- **Layer 0 (Canvas)**: Baseline tone `#FAF8F5`.
- **Layer 1 (Sub-tier panels & Media trays)**: `#F3EFEA` bordered with 1px `#E2DDD6`.
- **Layer 2 (Floating sheets, overlays, drawers)**: Crisp `#FFFFFF` surfaces wrapped with a 1px solid `#121212` perimeter outline.
- **Glass / Scrims**: Used only for fullscreen video viewports, featuring an obsidian scrim (`rgba(18, 18, 18, 0.85)`) with a low `backdrop-blur(8px)`.

## Shapes
The shape system is strictly architectural and brutalist (`roundedness: 0`). Sharp 90-degree corners communicate permanence, high editorial craftsmanship, and cinematic framing.

- Images, video containers, interactive buttons, modal frames, and index badges must adhere strictly to `border-radius: 0px`.
- Circular geometric exceptions are reserved solely for floating playheads, cursor trackers, and live audio waveform pucks.

## Components

### Buttons
- **Primary**: Solid `#121212` background, `#FAF8F5` text, 0px border radius, uppercase tracked label (`Jost`, 12px), generous horizontal padding (`1.75rem` x `1rem`). Hover state: background shifts to `#C2623D` with smooth color transition.
- **Secondary / Ghost**: Transparent background, 1px `#121212` hairline border, `#121212` text. Hover state: fills `#121212` with `#FAF8F5` text.
- **Text Action**: Uppercase tracked underline link with directional indicator (e.g., `EXPLORE REEL →`), border-bottom offset by `4px`.

### Index Tags & Chips
- Tracked uppercase tags in `Jost` featuring padded numerals (`01`, `02.1`, `AUDIO / MASTER`).
- Micro 1px border (`#D9CFC4`), transparent background, padding `0.25rem 0.5rem`.
- Active or Live states: bordered in `#C2623D` with text in `#C2623D`.

### Cards & Project Frames
- Flat `#FAF8F5` or `#F3EFEA` surfaces framed by a 1px `#E2DDD6` outer line.
- Image/video aspect ratio locked to `16:9` or `4:5` cinema framing.
- Header lockup inside card features the numerical index (`01`) floating top-left in `Jost`, followed by the project title in `Cormorant Garamond` below the frame.

### Lists & Tables
- Editorial archive table format: full-width rows divided by 1px `#E2DDD6` rules.
- Columns explicitly designated: `[00] INDEX`, `[TITLE]`, `[DIRECTOR / CLIENT]`, `[DISCIPLINE]`, `[YEAR]`.
- Row hover triggers an immediate subtle background shift to `#F0ECE5` and displays floating asset preview thumbnails.

### Form Inputs
- Stark underline or fully boxed input fields with 1px `#D9CFC4` border.
- Background: transparent `#FAF8F5`.
- Focus state: border transitions immediately to 1px `#121212` (no glow rings).
- Labels positioned outside the field in `label-sm` Jost.

### Audiovisual Media Strip & Timecodes
- Custom media progress bar: 1px continuous rule across the bottom of video tiles.
- Scrubber handle: 2px wide vertical tick in `#C2623D`.
- Running timecode metadata displayed in Jost (e.g., `00:04:12:08 // REC`).