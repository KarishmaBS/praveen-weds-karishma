---
name: Royal South Indian Temple Nuptials
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#524344'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#857374'
  outline-variant: '#d7c1c2'
  surface-tint: '#8d4b52'
  primary: '#410f18'
  on-primary: '#ffffff'
  primary-container: '#5c242c'
  on-primary-container: '#d88a91'
  inverse-primary: '#ffb2b9'
  secondary: '#775a00'
  on-secondary: '#ffffff'
  secondary-container: '#fece57'
  on-secondary-container: '#735700'
  tertiary: '#460614'
  on-tertiary: '#ffffff'
  tertiary-container: '#631d28'
  on-tertiary-container: '#e4838c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdadc'
  primary-fixed-dim: '#ffb2b9'
  on-primary-fixed: '#3a0913'
  on-primary-fixed-variant: '#70343c'
  secondary-fixed: '#ffdf98'
  secondary-fixed-dim: '#eec14b'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5a4300'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b8'
  on-tertiary-fixed: '#3f020f'
  on-tertiary-fixed-variant: '#792e38'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: 0.12em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: 0.1em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: 0.15em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0.12em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: 0.1em
  title-lg:
    fontFamily: EB Garamond
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.08em
  body-lg:
    fontFamily: EB Garamond
    fontSize: 19px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: 0.02em
  body-md:
    fontFamily: EB Garamond
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0.02em
  label-lg:
    fontFamily: Playfair Display
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.22em
  label-md:
    fontFamily: Playfair Display
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.18em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
This design system translates the sacred architectural majesty, devotional warmth, and heritage craftsmanship of a South Indian wedding into an immersive digital invitation suite. Rooted in traditional Dravidian temple iconography (Gopurams, Temple Elephants, Kuberakshi motifs, and ornate brass oil lamps), the aesthetic blends heirloom wedding stationery tactile qualities with digital interactivity. 

The visual style is **Tactile Editorial Luxury**, synthesizing antique gold foil stamping, embossed cotton rag paper finishes, rich madder-red burgundy borders, and ceremonial balance. The target audience comprises esteemed family members, global diaspora guests, and friends expecting a deeply cultural yet impeccably polished experience. The UI evokes reverence, timeless royalty, intimate hospitality, and sacred celebration.

## Colors
The palette draws straight from raw silk bridal Kanjeevarams, temple sanctum walls, and handcrafted gold jewelry:

- **Primary (`#5C242C`)**: Deep Royal Burgundy / Kumkum Marsala. Serves as the primary structural frame, formal text color, and primary decorative linework.
- **Secondary (`#C59B27`)**: Antique Gold / Swarna foil. Utilized for ceremonial accents, monograms, interactive buttons, highlight markers, and filigree motifs.
- **Tertiary (`#8A3B45`)**: Soft Rose Burgundy. Applied for secondary hierarchy, hover treatments, and subtle divider glyphs.
- **Neutral (`#FAF6F0`)**: Warm Ivory / Sandalwood Raw Cotton. Forms the canvas backdrop, preserving organic warmth and avoiding clinical digital white.
- **Text & Borders**: High-contrast contrast using deep ink burgundy (`#361217`) for crisp reading against ivory cards.

## Typography
Typographic rhythm mirrors traditional formal letterpress invitations. All headline and display elements leverage `Playfair Display` set in wide tracking with all-caps styling for couple names, event dates, and structural headers, creating a ceremonial feel.

Body copy and devotional verses use `EB Garamond`, offering high legibility and classical proportion. For dates, time stamps, and venue names, letter-spacing is exaggerated (`0.15em` to `0.22em`) to echo gold leaf embossing standards.

## Layout & Spacing
The layout follows a centered, ritualistic alignment characteristic of Indian heirloom wedding scrolls and invitations. 

- **Outer Canvas**: Centered single-column card layout constrained to a maximum width of 580px on desktop and tablet, simulating an authentic physical portrait wedding card (`1:1.414` or `4:5` ratio).
- **Framing Inset**: Every invitation module is surrounded by an outer 24px–32px safe zone enclosed by dual vintage ornamental hairline borders.
- **Rhythm & Breaks**: Vertical pacing relies on floral crests, Kalasam icons, and botanical divider glyphs rather than plain blank lines.
- **Adaptive Reflow**: On mobile viewports (`<480px`), outer margins compress to `1.25rem` while preserving ornamental inner margins of `1rem`, ensuring elaborate vine borders never clip critical wedding information.

## Elevation & Depth
Elevation mimics pressed cotton stock, metallic hot-stamping, and layered paper goods rather than digital drop shadows:

- **Surface Base**: `#FAF6F0` textured matte background featuring subtle micro-noise simulating 300gsm textured linen card stock.
- **Card Enclosure**: Dual inset border with an outer 12px solid burgundy matte frame (`#5C242C`) and an inner 1px hairline antique gold stroke (`#C59B27`) with floral corner spandrels.
- **Emboss Effect**: Important callouts (date chips, primary RSVP actions) employ an inner bevel shadow `inset 0 1px 2px rgba(255, 255, 255, 0.4), inset 0 -1px 2px rgba(0, 0, 0, 0.25)` and a subtle ambient gold cast `0 8px 24px rgba(92, 36, 44, 0.08)`.
- **Foil Emulation**: Monograms and decorative accents use a gentle metallic linear gradient transition between `#D4AF37`, `#F3E5AB`, and `#C59B27`.

## Shapes
Shapes maintain classical discipline with crisp or subtly softened edges (`roundedness: 1`), keeping corner radii between `0px` and `4px`. Cards, modal overlays, and invitation sheets maintain formal straight edges, while buttons, image frames, and itinerary badges use softly chamfered corners or traditional temple arch cut-outs (ogee arch / mandap curve profiles) rendered via SVG clipping paths.

## Components

### Action Buttons (RSVP & Map Navigation)
- **Primary Button**: Solid deep burgundy `#5C242C` background, crisp 1px gold border `#C59B27`, uppercase `Playfair Display` label in warm ivory `#FAF6F0` with `0.2em` letter spacing. Padding: `14px 28px`. Hover initiates a soft antique gold shimmer sweep.
- **Secondary Button**: Ivory background, 1.5px `#C59B27` border, typography in `#5C242C`.

### Ornamental Dividers & Borders
- **Ceremonial Flourish**: Horizontal filigree divider with central lotus, temple bell, or paisley finial in antique gold `#C59B27`.
- **Corner Spandrels**: Intricate Victorian/Dravidian leaf corner brackets framing all primary content modules.

### Event Cards & Itinerary Modules
- Contained within light sandalwood cards (`#FDFBF7`) bordered by a 0.5px burgundy border. Features ceremony name (Muhurtham, Reception), time chip with gold borders, and location details with direct Google Maps integration.

### Form Inputs (RSVP / Wishes)
- Inputs feature transparent backgrounds, a bottom-only 1px hairline border in `#8A3B45`, and floating labels in `EB Garamond`. Focus transitions the line to solid `#C59B27` with zero standard browser glow.

### Interactive Additions
- **Tamil / English Monogram Seal**: Circular royal crest linking "P" and Tamil "க" (Ka) with embossed foil treatment.
- **Calendar Add & Directions Chip**: Compact pill chip with gold foil border and small serif typography for one-click calendar sync.