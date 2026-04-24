---
version: alpha
name: Chutes
source_url: https://chutes.ai
last_inspected: 2026-04-23
brand_archetype: cinematic dark AI infrastructure with spectral 3D compute objects
colors:
  primary: '#8BFFC6'
  secondary: '#B4C1EE'
  accent: '#FFAB96'
  background: '#0C0C0C'
  foreground: '#FAFAFA'
  muted: '#9C9C9C'
  backgroundPage: '#0C0C0C'
  backgroundDeep: '#000000'
  backgroundSection: '#0D0D0D'
  surface: '#121212'
  surfaceElevated: '#171717'
  surfaceMuted: '#1C1C1C'
  textPrimary: '#FAFAFA'
  textSecondary: '#E0E0E0'
  textMuted: '#9C9C9C'
  textFaint: '#4A4A4A'
  textInverse: '#0D0D0D'
  borderSubtle: '#262626'
  borderStandard: '#343434'
  borderStrong: '#4A4A4A'
  brandMint: '#8BFFC6'
  brandPapaya: '#FFAB96'
  brandMountain: '#B4C1EE'
  brandDarkMountain: '#22232A'
  spectralCyan: '#22D3EE'
  spectralBlue: '#3080FF'
  spectralIndigo: '#625FFF'
  spectralPurple: '#A855F7'
  spectralMagenta: '#F472B6'
  spectralAmber: '#FBBF24'
  success: '#22C55E'
  warning: '#FBBF24'
  danger: '#EF4444'
typography:
  display:
    fontFamily: Tomato Grotesk, system-ui, sans-serif
    fontSize: 72px
    lineHeight: '0.98'
    fontWeight: 600
    letterSpacing: -0.04em
  h1:
    fontFamily: Tomato Grotesk, system-ui, sans-serif
    fontSize: 64px
    lineHeight: '1.00'
    fontWeight: 600
    letterSpacing: -0.035em
  h2:
    fontFamily: Tomato Grotesk, system-ui, sans-serif
    fontSize: 48px
    lineHeight: '1.05'
    fontWeight: 600
    letterSpacing: -0.03em
  h3:
    fontFamily: Tomato Grotesk, system-ui, sans-serif
    fontSize: 28px
    lineHeight: '1.15'
    fontWeight: 600
    letterSpacing: -0.02em
  body:
    fontFamily: Neue Haas Unica, ui-sans-serif, system-ui, sans-serif
    fontSize: 16px
    lineHeight: '1.625'
    fontWeight: 400
  bodyLarge:
    fontFamily: Neue Haas Unica, ui-sans-serif, system-ui, sans-serif
    fontSize: 18px
    lineHeight: '1.625'
    fontWeight: 400
  ui:
    fontFamily: Neue Haas Unica, ui-sans-serif, system-ui, sans-serif
    fontSize: 14px
    lineHeight: '1.4'
    fontWeight: 500
  badge:
    fontFamily: Neue Haas Unica, ui-sans-serif, system-ui, sans-serif
    fontSize: 13px
    lineHeight: '1.2'
    fontWeight: 500
    letterSpacing: 0.01em
  mono:
    fontFamily: Commit Mono, JetBrains Mono Nerd Font, ui-monospace, monospace
    fontSize: 13px
    lineHeight: '1.45'
    fontWeight: 400
rounded:
  none: 0px
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px
spacing:
  px: 1px
  1: 4px
  2: 8px
  3: 12px
  4: 16px
  5: 20px
  6: 24px
  8: 32px
  10: 40px
  12: 48px
  16: 64px
  20: 80px
  24: 96px
  32: 128px
components:
  buttonPrimary:
    backgroundColor: '{colors.foreground}'
    textColor: '{colors.textInverse}'
    typography: ui
    rounded: pill
    padding: 12px 18px
    height: 44px
  buttonSecondary:
    backgroundColor: '{colors.surface}'
    textColor: '{colors.textPrimary}'
    typography: ui
    rounded: pill
    padding: 12px 18px
    height: 44px
  buttonMint:
    backgroundColor: '{colors.brandMint}'
    textColor: '{colors.textInverse}'
    typography: ui
    rounded: pill
    padding: 12px 18px
    height: 44px
  badgeAnnouncement:
    backgroundColor: '{colors.surface}'
    textColor: '{colors.brandMint}'
    typography: badge
    rounded: pill
    padding: 8px 12px
  card:
    backgroundColor: '{colors.surface}'
    textColor: '{colors.textPrimary}'
    rounded: lg
    padding: 24px
  cardDense:
    backgroundColor: '{colors.backgroundSection}'
    textColor: '{colors.textPrimary}'
    rounded: md
    padding: 16px
  pricingFeatured:
    backgroundColor: '{colors.surface}'
    textColor: '{colors.textPrimary}'
    rounded: xl
    padding: 28px
  heroVisualFrame:
    backgroundColor: '{colors.backgroundDeep}'
    textColor: '{colors.textPrimary}'
    rounded: xl
    padding: 0px
---

## Overview

Chutes is a dark-mode-native AI infrastructure brand: serverless GPU compute, open-source models, production scale, and developer trust. The site reads as premium and technical, but its signature is not a generic dashboard screenshot. It uses cinematic black surfaces and recurring iridescent 3D cube imagery to turn compute into an art-directed object: modular, spectral, powerful, and futuristic.

Evidence inspected from https://chutes.ai: homepage hero, navigation, announcement strip, partner/model grids, hyperscale feature cards, pricing section, page metadata, CSS variables, stylesheet font declarations, and image assets. Observed fonts include Tomato Grotesk, Neue Haas Unica, Commit Mono, JetBrains Mono Nerd Font, Power Grotesk, and Season Mix. Observed CSS tokens include ink blacks (#0C0C0C, #121212), papaya (#FFAB96), mountain (#B4C1EE), dark mountain (#22232A), and visible mint text around rgb(139, 255, 198).

Closest archetypes: Linear for dark precision, VoltAgent for developer-infrastructure darkness and green signal accents, Runway for cinematic image-led atmosphere. Chutes differs through its spectral 3D cube grammar and open-source model marketplace/catalog density.

Brand adjectives: cinematic, spectral, developer-native, scalable, premium, open-source-aligned, calm.

## Colors

Use near-black as the native medium. Most interface surfaces should sit within a narrow luminance range: page #0C0C0C, sections #0D0D0D, cards #121212, elevated cards #171717. White and off-white type should do most of the hierarchy work. Mint (#8BFFC6) is the primary product accent and should feel like a live compute/status signal, not a decorative wash.

Primary palette:
- Page black: #0C0C0C
- Deep black: #000000
- Card surface: #121212
- Elevated surface: #171717
- Primary text: #FAFAFA
- Secondary text: #E0E0E0
- Muted text: #9C9C9C
- Border: #262626 / #343434
- Mint signal: #8BFFC6
- Papaya warmth: #FFAB96
- Mountain lavender: #B4C1EE
- Dark mountain: #22232A

Spectral image palette:
- Cyan #22D3EE
- Electric blue #3080FF
- Indigo #625FFF
- Purple #A855F7
- Magenta #F472B6
- Amber #FBBF24

Usage ratios for UI: 72% near-black, 16% white/off-white text, 8% charcoal borders/surfaces, 3% mint signal, 1% papaya/mountain/spectral accents. In hero imagery, the spectral colors can rise to 20-35% because they are contained in the 3D object or atmospheric bloom.

## Typography

Headlines should use Tomato Grotesk or a close geometric grotesk substitute. They are large, compressed, and confident. Use tight line-height and negative tracking; avoid soft editorial serif treatments. Body and UI text should use Neue Haas Unica or a high-quality neo-grotesk fallback such as Inter, system-ui, or Helvetica Neue.

Recommended hierarchy:
- Hero display: 64-72px, Tomato Grotesk, 600, line-height 0.98-1.0, tracking -0.035em to -0.04em.
- Section heading: 40-48px, Tomato Grotesk, 600, line-height 1.05, tracking -0.03em.
- Card heading: 22-28px, Tomato Grotesk, 600, line-height 1.15.
- Body: 16-18px, Neue Haas Unica, line-height 1.625, color #C4C4C4 to #E0E0E0.
- UI labels: 13-14px, Neue Haas Unica, 500, compact line-height.
- Code/API snippets: Commit Mono or JetBrains Mono, 12-14px.

Copy should be direct and scale-focused: “Breakthrough Serverless Compute for AI, At Scale,” “Top models are live,” “Made for hyperscaling AI powered products,” “SOTA Open-Source LLMs.” Keep claims concrete and production-oriented.

## Layout

Use a centered, cinematic SaaS landing structure:
- Sticky dark nav with restrained dropdowns and pill CTAs.
- Centered hero: announcement pills, huge headline, short technical subhead, 1-2 CTAs.
- Large visual anchor below hero: iridescent cube or product/compute object on black atmospheric background.
- Dense proof modules: partner strips, model cards, and logo grids.
- Three-column feature cards for platform values.
- Product/catalog grids with compact cards and metadata.
- Four-column pricing table with one featured mint-accented tier.
- Multi-column footer, dark and quiet.

Container widths should generally stay between 1120px and 1280px. Major vertical sections need 80-128px spacing; card grids can be dense with 16-24px gaps. Let the black canvas be the whitespace.

## Elevation & Depth

Depth comes from luminance steps, borders, glow, and cinematic imagery rather than conventional box shadows. Standard cards should use #121212 with a #262626 border. Featured states may use a mint border, faint mint glow, or a spectral background bloom.

Hero/image depth rules:
- Use black-to-indigo atmospheric gradients behind 3D objects.
- Add soft bloom and rim light around cube edges.
- Use holographic reflections on the object, but keep UI chrome restrained.
- Avoid generic SaaS drop shadows; use subtle borders and background luminance instead.

Suggested CSS effects:
- Card border: 1px solid #262626.
- Elevated card: background #171717, border #343434.
- Mint focus: 0 0 0 1px rgba(139,255,198,0.5), 0 0 24px rgba(139,255,198,0.10).
- Spectral bloom: radial-gradient at center with rgba(98,95,255,0.18), rgba(34,211,238,0.10), transparent.

## Shapes

Geometry is modern and restrained. Use pills for CTAs, announcement badges, and status chips. Use 8-16px radius for cards and visual frames. Avoid highly playful blob shapes in the interface. The organic energy belongs in the iridescent cube texture, not in the UI chrome.

Radius scale:
- 4px: code chips, tiny controls.
- 6px: compact buttons, small inputs.
- 8px: dense model cards.
- 12px: feature cards.
- 16px: pricing cards and image frames.
- 9999px: pills and badges.

## Components

Navigation:
Use dark transparent/black nav, left logo lockup, Product/Resources/Company/Pricing links, and right-aligned CTA buttons. Links are small, clean, and low-noise. The active CTA can be white-on-black inverse or light fill on dark.

Announcement pills:
Rounded, compact, dark surface with mint label treatment. Pair a short product marker with a chevron or tiny icon. They should feel like live platform updates.

Hero:
Centered text, max-width around 900px. Headline should dominate. The subhead should be one concise paragraph. CTAs should sit under copy with generous spacing, then a small trust/provenance row such as Chutes Global / Bittensor.

Cards:
Use dark cards with thin borders, muted metadata, and strong logo/visual centers. Model cards can be dense and repeated; feature cards should be quieter, with a plus icon or concise title/description pattern.

Pricing:
Four dark cards, one highlighted by mint border/accent. Use checkmark lists, restrained pricing numerals, and pill CTAs. Avoid loud gradients in pricing; keep it conversion-clear.

Imagery:
The core brand image is the spectral compute cube: black environment, iridescent/rippled material, purple-blue haze, cyan/magenta/amber reflections, soft bloom, premium 3D render quality. Secondary imagery may include AI-generated sample images, model/provider logos, and abstract compute-network forms.

## Do's and Don'ts

Do:
- Build dark-first; never treat dark mode as an afterthought.
- Use Tomato Grotesk-style compressed headlines and Neue Haas-style clean body copy.
- Reserve mint for status, emphasis, CTAs, and live/product-update cues.
- Make spectral cube imagery the hero signature.
- Use dense model/catalog grids to communicate breadth and ecosystem scale.
- Keep copy technical, short, and confidence-led.
- Use subtle borders instead of heavy shadows.
- Keep motion slow: ticker strips, logo/model carousels, gentle glow or cube shimmer.

Don't:
- Do not use flat generic blue SaaS gradients as the main identity.
- Do not use cartoon AI robots, neural-network clip art, or friendly mascot illustrations.
- Do not flood UI with rainbow; spectral color belongs mostly inside hero/image assets.
- Do not use serif editorial typography for core product pages.
- Do not make cards overly rounded or bubbly.
- Do not use bright white full-page backgrounds except for rare documentation/help contexts.
- Do not over-explain with long paragraphs; Chutes’ voice is compact and operational.
