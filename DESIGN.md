# Design system — Silicon Valley Smile Solutions

World: category-standard premium dental, warm and neighborly. Light, photo-led, generous whitespace.

## Color
- `--ink` #15302E deep evergreen (text, primary buttons, dark bands)
- `--pine` #1E5C55 brand primary (links, accents on light)
- `--mint` #DDEEE8 soft brand tint (section grounds, chips)
- `--sand` #F6F1EA warm neutral section ground
- `--paper` #FFFFFF main ground
- `--honey` #E7A83E warm accent: star ratings and the single highlight per view only
- `--muted` #4F625F secondary text (≥4.5:1 on paper and sand)
Strategy: restrained. Evergreen carries structure; honey is rationed.

## Type
- Display: Young Serif (headings only, never below 1.25rem)
- Text/UI: Figtree 400/500/600/700
- Scale: 3.75 / 2.75 / 2 / 1.375 / 1.125 / 1 / .875 rem

## Shape & depth
- Radius: 14px cards/images, 999px buttons and chips
- Shadow: 0 18px 40px -18px rgba(21,48,46,.28) for lifted elements only

## Components
- Primary button: evergreen pill, white text; hover lifts 1px, deepens.
- Secondary: outline pill in evergreen.
- Placeholders: any unconfirmed fact wrapped in `.ph` (dotted honey underline, tooltip). Remove the class once the owner confirms.

## Motion
One entrance: hero content fades up on load. Everything else static; respect prefers-reduced-motion.
