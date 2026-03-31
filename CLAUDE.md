# Awai Atelier — Custom Shopify Theme

## Brand Identity
Awai Atelier is a nursery design studio. We 3D print lighting and 
sculpture from plant-based PLA. Our aesthetic is soft, elevated, 
Scandinavian-meets-cloud-world. Warm, never cold. Sculptural, never 
cute. Gallery-like, never cluttered.

## Design System

### Typography
- Display/Headings: Quicksand (Google Fonts) — weights 300, 400, 500, 600, 700
- Body: Plus Jakarta Sans (Google Fonts) — weights 200, 300, 400, 500, 600
- Code/Specs: JetBrains Mono (only if needed)

### Color Palette
Core:
- Vanille: #EDE8D6 (warm canvas, backgrounds)
- Vanille Soft: #F5F1E6 (lighter backgrounds)
- Crème de Citron: #E8E0B0 (warm signal, accents)
- Cloud: #C0CEDC (cool anchor)
- Sage: #C8D0B8 (earthy ground)

Supporting:
- Lila: #D5D0DE (cool lavender)
- Blush: #DED4D8 (whisper pink)
- Mist: #D0CDD6 (lavender-gray)

Neutrals:
- Cocoa: #3D3835 (primary text, dark elements)
- Dusk: #5A5550 (body text)
- Haze: #8A8580 (captions)
- Fog: #B5B0AA (placeholder text)
- Cirrus: #F7F5F1 (surface backgrounds)
- Cumulus: #FDFCFA (page background)

### Spacing
- Base-8 system: 8, 16, 24, 40, 64, 96, 140px
- Border radius: 16px (small), 22px (cards), 28px (sections), 200px (pills/buttons)
- Card padding: 20-24px
- Section padding: 100-140px vertical
- Content max-width: 1100-1200px
- Body text max-width: 580px

### Design Principles
- Generous negative space — layouts should breathe
- Scroll-reveal animations (subtle translateY, 0.6s ease)
- No heavy gradients or blobs on backgrounds
- Product images treated as sculptural objects, not catalog shots
- FDM ribbed texture pattern used as decorative element

### Brand Voice
- Warm, playful, specific
- Sky-world vocabulary: float, drift, lift, cloud, balloon
- "Awai" wordplay: drift-Awai, far and Awai, up up and Awai
- One wordplay per headline maximum
- Never: exclamation points, urgency language, "shop now", "limited edition"
- Period at end of taglines: "Up, Up and Awai."

### Collections
- Collection 01: "Up, Up and Awai." — Hot air balloon lamp + sculpture
- Future: "Far and Awai" (adventure), "Drift-Awai" (sleep), "Stow-Awai" (storage)

## Technical Notes
- This is a Shopify theme built on Dawn
- Use Liquid templating for dynamic content
- All product data comes from Shopify admin (don't hardcode prices/names)
- Google Fonts loaded via <link> in theme.liquid
- CSS custom properties for all colors (match the palette above)
- Sections should be customizable via Shopify's theme editor where possible
