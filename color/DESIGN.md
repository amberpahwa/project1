---
name: Warm Pastel Collective
colors:
  surface: '#fbf8ff'
  surface-dim: '#dbd9e1'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2fb'
  surface-container: '#efecf5'
  surface-container-high: '#eae7ef'
  surface-container-highest: '#e4e1ea'
  on-surface: '#1b1b21'
  on-surface-variant: '#56423c'
  inverse-surface: '#303036'
  inverse-on-surface: '#f2eff8'
  outline: '#89726b'
  outline-variant: '#ddc0b8'
  surface-tint: '#9f4122'
  primary: '#9f4122'
  on-primary: '#ffffff'
  primary-container: '#ff8a65'
  on-primary-container: '#752305'
  inverse-primary: '#ffb59e'
  secondary: '#6550a6'
  on-secondary: '#ffffff'
  secondary-container: '#b9a3ff'
  on-secondary-container: '#493488'
  tertiary: '#006c4b'
  on-tertiary: '#ffffff'
  tertiary-container: '#4ebe8f'
  on-tertiary-container: '#004931'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59e'
  on-primary-fixed: '#3a0b00'
  on-primary-fixed-variant: '#7f2a0d'
  secondary-fixed: '#e8deff'
  secondary-fixed-dim: '#cdbdff'
  on-secondary-fixed: '#20005f'
  on-secondary-fixed-variant: '#4c388c'
  tertiary-fixed: '#8af8c5'
  tertiary-fixed-dim: '#6ddbaa'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#fbf8ff'
  on-background: '#1b1b21'
  surface-variant: '#e4e1ea'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 36px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1.25rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
The design system powers an expressive, energetic, yet warm collective portfolio for creative squads and friend groups. It targets culturally engaged peers, creative directors, collaborators, and clients looking for human-centered talent. The visual voice avoids sterile agency clichés in favor of friendly optimism, youthful tactility, and editorial polish.

The aesthetic synthesizes modern minimalism with expressive tactile softness:
- **Clean Foundation:** Balanced whitespace, structured typographic scales, and restrained line layouts maintain clear navigation and readability on small viewports.
- **Warm & Tactile Vibrancy:** Friendly pill containers, delicate colored outlines, and gentle pastel accents impart charm without veering into juvenile territory.
- **Social Dynamism:** Interactive touch targets utilize pill shapes, buoyant micro-interactions, and clear states crafted specifically for thumb-driven mobile interaction.

## Colors
The palette balances an inviting warm cream canvas with punchy, tasteful pastel pigments and rich contrast text:

- **Primary (`#FF8A65` — Soft Apricot):** The focal energy driver for primary actions, prominent badges, active tabs, and squad highlights.
- **Secondary (`#9D88E2` — Electric Lavender):** Used for collaborator tags, secondary interactions, project category chips, and creative disciplines.
- **Tertiary (`#56C596` — Mint Accent):** Reserved for live status indicators ("Available for projects", "Streaming now"), playful stickers, and verification markers.
- **Neutral (`#1E1E24` — Deep Charcoal):** Provides grounding structure for high-contrast typography, high-impact icons, and crisp outlines, ensuring strict WCAG AAA legibility against cream surfaces.
- **Surfaces & Canvas:** Backgrounds sit on a curated ivory-cream base (`#FAF7F2`), layered with crisp white cards (`#FFFFFF`) and delicate tinted sub-surfaces (`#F3EFEA` and `#F8F3FC`) to establish natural visual hierarchy without heavy gray drops.

## Typography
The typographic architecture pairs the welcoming, friendly geometry of **Plus Jakarta Sans** with the structural, modern energy of **Space Grotesk**:

- **Plus Jakarta Sans** commands display headers, intro texts, and narrative body copy. Its open counters and geometric warmth make squad member bios and project descriptions approachable and engaging.
- **Space Grotesk** serves as the utility engine for tags, member roles, metadata, timestamps, and interactive labels. Its subtly technical personality injects creative distinction and crisp data hierarchy across compact mobile cards.

## Layout & Spacing
The layout follows a mobile-first fluid grid optimized for vertical scroll dynamics, one-handed thumb reach, and horizontal media carousels.

- **Grid Architecture:** 4 fluid columns on mobile viewports with `16px` (`1rem`) gutters and `20px` (`1.25rem`) screen boundary margins. On compact devices (width < 360px), gutters adjust to `12px` and outer margins to `16px`.
- **Rhythm & Touch:** Internal component gaps prioritize consistent fingertip targets (minimum 44px vertical touch targets). Outer section separators use `space-xl` (`32px`) to preserve rhythmic breathing room between member spotlights, collaborative galleries, and collective manifesto blocks.
- **Horizontal Carousels:** Media reels and squad avatar tracks use negative margin bleed with leading padding equal to `margin` (`1.25rem`), enabling edge-to-edge swiping while maintaining inline grid alignment on initial load.

## Elevation & Depth
Depth relies on a tactile blend of tinted ambient illumination and low-contrast borders rather than traditional dark drops:

- **Tonal Layering:** The primary canvas rests on warm cream (`#FAF7F2`). Elevated containers transition to clean white (`#FFFFFF`) or soft pastel-tinted cards (`#FFF4EF` for apricot glow, `#F6F3FC` for lavender glow).
- **Ambient Tinted Shadows:** Cards and floating action elements cast warm, ultra-soft shadows tinted with neutral charcoal and faint apricot undertones (`box-shadow: 0 8px 24px -4px rgba(30, 30, 36, 0.06), 0 4px 12px -2px rgba(255, 138, 101, 0.08)`).
- **Hairline Framing:** Interactive cards utilize low-contrast hairline borders (`1px solid rgba(30, 30, 36, 0.08)`) to preserve clean silhouettes across all light conditions.
- **Pressed & Active Feedback:** Touch triggers compress vertically by `1px` to `2px` with an elevation reduction (`box-shadow: 0 2px 6px rgba(30, 30, 36, 0.08)`), delivering instantaneous tactile response.

## Shapes
A level 3 (pill-shaped) geometry anchors the collective's warm, playful personality:

- **Pills (`rounded-full` / 9999px):** Standard for buttons, social pills, status chips, discipline tags, search bars, and floating controls.
- **Large Pill Containers (`rounded-xl` / 32px):** Applied to primary squad bio cards, portfolio case-study cards, and modal presentation sheets.
- **Media & Avatar Shapes:** Member avatars use either full circles (`rounded-full`) or squircle pill frames (`rounded-xl`), framed with thick cream strokes (`3px solid #FAF7F2`) when stacked in mutual collaborative groups.

## Components

### Buttons
- **Primary Pill:** Background in Soft Apricot (`#FF8A65`) with Deep Charcoal text (`#1E1E24`), bold `Space Grotesk` label (`label-lg`), and subtle warm ambient shadow. Minimum height 48px with generous inline padding (`1.5rem`).
- **Secondary Pill:** Electric Lavender outline or soft wash (`#F3EFEA` background, `#1E1E24` text, `1px solid rgba(30, 30, 36, 0.12)`).
- **Social Pill Buttons:** Full-pill containers housing the platform icon alongside a concise handle or action label. Styled with white background, subtle border, and deep charcoal glyphs that subtly tint toward the squad's apricot on press.

### Chips & Badges
- **Role & Discipline Badges:** Compact full-pill shapes with uppercase `Space Grotesk` (`label-sm`). Backgrounds use low-saturation pastel washes (e.g., `#F4F0FD` with `#7860C4` text for Art Direction; `#FFF1EC` with `#D86B46` text for 3D Design).
- **Status Indicator Pill:** Tertiary Mint (`#56C596`) pulsing micro-dot paired with `"Open for collaborations"` text in Deep Charcoal.

### Cards
- **Squad Member Pill Card:** White background, 24px inner padding, `32px` border radius (`rounded-xl`), and low-contrast border. Displays the member's visual avatar, nickname, creative roles as pills, brief intro, and rapid social touch links.
- **Portfolio Showcase Card:** Features top-weighted media framed with `24px` radius, followed by title, collaborative credits (showing member avatar stacks), and a lavender or apricot category chip.

### Inputs & Search
- **Search & Quick-Connect Fields:** Enclosed in full-pill containers (`rounded-full`) with a soft ivory-white fill (`#FFFFFF`), `1px solid rgba(30,30,36,0.12)`, and prominent placeholder text in charcoal with 50% opacity. Focused states shift border color to `#9D88E2` with a diffuse lavender focus ring.

### Lists & Collaborator Stacks
- **Collaborator Roll:** Flat list items separated by thin ivory-cream rules. Includes interactive trailing chevron pills for drill-down navigation into specific member folios.
- **Stacked Avatar Badges:** Overlapping circular profile images with negative overlap (`-8px`), cleanly outlined in cream background color to preserve separation.