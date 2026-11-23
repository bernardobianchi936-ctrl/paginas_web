---
name: Eventos ALE
description: One evening of service in La Paz, from candle-gold banquet light to the cyan neon of the bar, ending at a WhatsApp quote.
colors:
  obsidian: "#0F1115"
  pizarra: "#161920"
  bar-night: "#0B0D11"
  oro: "#D4AF37"
  oro-claro: "#E6C866"
  neon: "#2DD4BF"
  hueso: "#F8FAFC"
  hueso-tenue: "#CBD5E1"
  niebla: "#94A3B8"
  field-line: "#2C313B"
  field-line-hover: "#3D4350"
  alerta: "#F87171"
typography:
  display:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "clamp(2.6rem, 7.2vw, 5.6rem)"
    fontWeight: 500
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "clamp(2rem, 4.4vw, 3.4rem)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.015em"
  title:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "1.875rem"
    fontWeight: 400
    lineHeight: 1.25
  wordmark:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.18em"
  body:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.625
    fontFeature: "\"ss01\""
  label:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 600
    lineHeight: 1.25
  caption:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.43
rounded:
  check: "6px"
  field: "12px"
  card: "16px"
  plate: "20px"
  pill: "9999px"
spacing:
  gutter: "20px"
  gutter-wide: "32px"
  grid-gap: "16px"
  plate-pad: "28px"
  plate-pad-wide: "36px"
  section: "96px"
  section-wide: "128px"
  container: "72rem"
components:
  button-primary:
    backgroundColor: "{colors.oro}"
    textColor: "{colors.obsidian}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "16px 28px"
  button-primary-hover:
    backgroundColor: "{colors.oro-claro}"
    textColor: "{colors.obsidian}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.hueso}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "16px 28px"
  button-ghost-hover:
    textColor: "{colors.oro}"
  button-neon:
    backgroundColor: "transparent"
    textColor: "{colors.neon}"
    rounded: "{rounded.pill}"
    padding: "14px 24px"
  button-neon-hover:
    backgroundColor: "{colors.neon}"
    textColor: "{colors.obsidian}"
  field:
    backgroundColor: "{colors.obsidian}"
    textColor: "{colors.hueso}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13.6px 16px"
  service-plate:
    backgroundColor: "{colors.obsidian}"
    textColor: "{colors.hueso}"
    rounded: "{rounded.plate}"
    padding: "{spacing.plate-pad}"
  event-option:
    backgroundColor: "transparent"
    textColor: "{colors.hueso}"
    rounded: "{rounded.card}"
    padding: "16px 20px"
  icon-disc:
    backgroundColor: "{colors.obsidian}"
    textColor: "{colors.oro}"
    rounded: "{rounded.pill}"
    size: "44px"
  nav-pill:
    backgroundColor: "rgba(15, 17, 21, 0.55)"
    textColor: "{colors.niebla}"
    rounded: "{rounded.card}"
    padding: "12px 24px"
---

# Design System: Eventos ALE

## Overview

**Creative North Star: "One Evening of Service"**

The page is a single night at a celebration in La Paz. It opens under warm banquet light: an obsidian room, photographs of food and set tables lit from within, and champagne gold used the way a good venue uses brass, in thin lines and small fixtures, never as wallpaper. When the drinks arrive the light changes: in the bar passage, and only there, a cyan neon tube is drawn as an arch around a cocktail photo and flickers on once. The evening then closes at the quote, where the form writes the WhatsApp message live in a bubble.

Density is generous and photographic. Sections breathe on tall vertical padding, headlines are large Playfair serif set left, and the real content is the photographs: full-bleed or tall framed plates with an obsidian gradient rising from the bottom so text can sit on the image. Interface chrome is quiet: dark glass, hairline borders at 7–10% white, pills for every action.

The system refuses the category default of a cream wedding-planner page with a centered headline over rows of identical icon cards. Text over photos is always set bottom-left on a gradient, and service content is carried by images, not by icons in boxes.

**Key Characteristics:**
- Two grounds (obsidian, pizarra) alternate by section; a darker bar-night ground belongs to the neon passage.
- Gold is a light source: hairlines, the primary action, icons, one accent phrase per headline.
- Cyan neon is local to the cocktail bar and always reads as emitted light (glow), never as flat UI color.
- Playfair Display speaks; Plus Jakarta Sans serves.
- Photographs are plates with bottom-up obsidian gradients; text sits at their foot.
- Motion is one rise-and-settle per section on a long, soft ease-out; the neon flickers on exactly once.

## Colors

A night palette: near-black slate grounds, one warm metal and one cold light, with cool off-white text.

### Primary
- **Champagne Gold** (oro): the house light. Fills the primary action, colors section hairlines, icon strokes, the italic accent word in headlines, the wordmark's second word, phone numbers and the focus ring. Text on gold is always obsidian.
- **Lit Champagne** (oro-claro): hover state of gold fills only.

### Secondary
- **Bar Neon Cyan** (neon): the cocktail bar's own light. Used for the neon arch stroke, the "Let's drink" sign line, the one neon word in the bar headline, bar feature icons, the bar's outline button, and the border and glowing icon disc of the bar service plate. Nowhere else.

### Neutral
- **Obsidian** (obsidian): page ground, hero gradient floor, form fields, footer, icon disc fill, text on gold or neon.
- **Slate Pizarra** (pizarra): alternate section ground (Eventos, Cotizar) and the open mobile menu.
- **Bar Night** (bar-night): a deeper ground used only by the bar passage so the neon reads brighter.
- **Bone** (hueso): headlines, primary text, labels.
- **Soft Bone** (hueso-tenue): body copy set over photographs, where the mist grey would lose contrast against the image.
- **Mist** (niebla): secondary copy on flat grounds, nav links at rest, captions, meta rows.
- **Field Line** (field-line) and **Field Line Hover** (field-line-hover): borders of inputs and checkbox options, at rest and on hover. Containers use translucent white hairlines instead (7–10% white).
- **Alert Coral** (alerta): field error border and error messages.

### Named Rules
**The Two Lights Rule.** Gold is the light of the whole evening; cyan is the light of the bar. Cyan appears only inside the bar passage and on the bar's own service plate. A surface that is not about the bar never carries cyan.

**The Brass Fixture Rule.** Gold is used in lines, small fills and words: hairlines, one primary button per view, icons, one accent phrase. It never fills a section, a card or a large background.

**The WhatsApp Exception.** WhatsApp's own colors (brand green on the floating button, its dark chat ground, outgoing-bubble green and bubble text) appear only where the page depicts WhatsApp itself. They are not part of the palette.

## Typography

**Display Font:** Playfair Display (with Georgia, serif)
**Body Font:** Plus Jakarta Sans (with system-ui, sans-serif), stylistic set ss01 on

**Character:** A high-contrast editorial serif for everything that is said, with a warm geometric sans for everything that is done. The serif carries italics for emphasis; the sans carries every control.

### Hierarchy
- **Display** (500, clamp(2.6rem, 7.2vw, 5.6rem), 1.02, −0.02em): the hero H1 only, max 14ch, bottom-left over the photo.
- **Headline** (400, clamp(2rem, 4.4vw, 3.4rem), 1.08, −0.015em): every section H2. Carries one accent phrase in gold (or neon in the bar), often italic.
- **Title** (400, 1.875rem rising to 2.3rem on the large plate, 1.25): plate and panel headings; smaller plates step down to 1.45–1.75rem. Event option names use 1.25rem.
- **Wordmark** (400, 1.25rem, 0.18em tracking, uppercase): "EVENTOS ALE" in the nav and footer, second word in gold.
- **Body** (400, 1rem–1.125rem, 1.625): paragraphs held to 44–56ch.
- **Label** (600, 0.95rem): buttons and option titles. Form labels use 500 at 0.875rem.
- **Caption** (400, 0.875rem): secondary lines, meta row, footer details; 0.75rem for photo chips and legal lines.

### Named Rules
**The Serif Speaks, Sans Serves Rule.** Headings, plate titles, the wordmark and the neon sign line are Playfair. Buttons, labels, fields, nav links and captions are Plus Jakarta Sans. Never set a control in the serif.

**The One Accent Phrase Rule.** A headline gets at most one colored phrase, and emphasis is italic serif, not bold.

## Layout

One centered column, max 72rem, with 20px side gutters (32px from 640px). Sections stack full-width with 96px vertical padding (128px from 640px) and alternate obsidian and pizarra grounds; the bar passage takes bar-night. Inside the column, content uses a 12-column grid from 768–1024px: headings span 7 with an intro paragraph in the remaining 5, aligned to the baseline; the quote section splits 5 (copy and message preview) to 7 (form).

The hero is a full-viewport (100svh) photograph with content pinned to the bottom-left; on phones an extra obsidian veil sits over the photo and the actions stack full-width, keeping the H1 and primary button in the first screen. Service plates form an asymmetric bento (one tall half-width plate, one wide plate, two quarter plates) that collapses to a single column. The gallery is a 2-up grid on phones and a 3-column grid with 15rem rows and one 2×2 lead photo from 768px. Grid gaps are 12–20px; plate interiors pad 24–36px.

Breakpoints follow Tailwind defaults: 640px, 768px, 1024px. The desktop nav links appear at 1024px; below that, a menu button opens a glass dropdown.

## Elevation & Depth

Depth comes from light and photographs, not from stacked cards. Surfaces are flat and separated by ground changes and translucent hairlines; the strongest depth cue is the bottom-up obsidian gradient on every photo. Shadows exist only as light or as the shadow of something floating: a gold glow under the primary action, the neon tube's three-layer glow, and soft dark ambients under the floating nav, menu, message preview and WhatsApp button.

### Shadow Vocabulary
- **Gold glow** (`box-shadow: 0 12px 30px -10px rgba(212,175,55,.55)`; submit uses `0 14px 34px -12px rgba(212,175,55,.6)`): under the hero and form primary buttons.
- **Neon glow** (`filter: drop-shadow(0 0 3px rgba(45,212,191,.9)) drop-shadow(0 0 14px rgba(45,212,191,.55)) drop-shadow(0 0 36px rgba(45,212,191,.35))`): the neon arch tube; the neon text uses `text-shadow: 0 0 6px rgba(45,212,191,.6), 0 0 22px rgba(45,212,191,.35)`; the bar icon disc uses `0 0 18px -2px rgba(45,212,191,.55)`.
- **Float ambient** (`box-shadow: 0 10px 40px -12px rgba(0,0,0,.6)`): the glass nav pill; the open menu and message preview use deeper versions of the same soft black.

### Named Rules
**The Lit, Not Lifted Rule.** A shadow is either emitted light (gold or neon glow) or the soft shadow of a floating layer. Cards and plates sit flat. No hard offset shadows.

## Shapes

Every action is a full pill. Photo containers are softly rounded plates (20px for service plates, 16px for gallery plates and event options), with the image clipped to the plate. Fields and checkbox options use 12px; checkbox boxes use 6px. Icon holders are circles with a gold (or neon) hairline ring. The one exception to the rounded-rectangle grammar is the neon arch: a photo clipped to a round-topped arch with a 14px base, outlined by the SVG tube. The arch belongs to the bar. Hairlines are 1px: 7–10% white on containers, 25% gold on the footer edge and hours table, and a 1px × 80px gold-to-transparent rule above section headlines.

## Components

### Buttons
Confident, warm and round; one gold action leads each view.
- **Shape:** full pill (9999px).
- **Primary:** gold fill, obsidian 600 label at 0.95rem, padding 16px × 28px, gold glow beneath; WhatsApp actions add the WhatsApp glyph, others a thin Lucide arrow.
- **Hover / Active / Focus:** fill lifts to Lit Champagne; press scales to 0.97–0.99; keyboard focus is a 2px gold outline offset 3px.
- **Ghost:** transparent with a 25% bone hairline and bone text; on hover the ring and text turn gold.
- **Neon (bar only):** transparent with a 60% neon ring and neon text; on hover it fills neon with obsidian text.

### Chips
- **Photo caption chip:** obsidian at 85% opacity, full pill, 0.75rem 500 bone text, pinned 12px from the bottom-left of a gallery plate.

### Cards / Containers
- **Service plate:** a photograph filling a 20px plate, a 7% white hairline (30% neon on the bar plate), an obsidian gradient rising from the foot, and a gold-ringed icon disc, serif title and soft-bone copy set at the bottom-left. The image eases to 1.06 scale on hover or focus-within over 1.2s.
- **Quote form shell:** obsidian at 70% on pizarra, 8% white hairline, 24–36px padding.
- **Shadow Strategy:** flat; see Elevation & Depth.

### Inputs / Fields
- **Style:** obsidian ground, 1px field-line border, 12px radius, 13.6px × 16px padding, 1rem bone text, gold caret; selects carry a gold chevron, the date picker icon is tinted gold.
- **Focus:** border turns gold with a 3px gold halo at 18%.
- **Error:** border turns Alert Coral, with a 0.875rem coral message below.
- **Checkbox option:** a 12px-rounded tile with a 6px box; checked fills the box gold with an obsidian tick and tints the tile 6% gold with a 60% gold border.

### Navigation
A floating dark-glass pill: obsidian at 55% with 24px backdrop blur and saturation, 10% white hairline, 16px radius, float ambient shadow, max 72rem and inset 12–20px from the top. Wordmark left with "by Alexis Carmona Catering" beneath in 0.68rem mist; mist links at 0.875rem turning bone on hover; the gold WhatsApp pill right (hidden on phones). Below 1024px a 40px circular menu button opens a pizarra glass dropdown with 12px-rounded rows and a full-width gold WhatsApp action.

### Event Selector (signature)
A vertical tablist of 16px-rounded options, each with a gold-ringed icon disc, a serif name and a mist line. The selected option tints 8% gold with a 55% gold border, fills its disc gold, and reveals a gold arrow. Beside it, a tall photo panel cross-fades its image and offers a gold "Cotizar mi …" button that preselects the event in the form and scrolls there.

### Neon Arch (signature, bar only)
A 3:4 cocktail photo clipped to a round-topped arch, outlined by a 3.5px cyan SVG tube with the neon glow, over a faint cyan bloom (7% neon, heavily blurred) on bar-night. It rests at 8% opacity and flickers on once (1.4s stepped) when it enters the viewport. A serif italic "Let's drink" in neon sits beneath as the sign.

### Message Preview
A depiction of the WhatsApp chat: dark chat ground, gold monogram avatar, and an outgoing green bubble (16px with a 4px top-right corner) that the form writes live. Shown beside the form on desktop and inside a disclosure on phones.

## Do's and Don'ts

### Do:
- **Do** alternate obsidian and pizarra grounds by section and give the bar passage bar-night.
- **Do** set text over photographs at the bottom-left on an obsidian gradient rising from the foot, in hueso and hueso-tenue.
- **Do** keep one gold primary pill per view, with obsidian text and the gold glow.
- **Do** give each section headline one accent phrase in gold (neon inside the bar), with italic serif as the emphasis.
- **Do** use Lucide icons at 1.6 stroke, in gold (neon in the bar), inside hairline-ringed circles when they label a block.
- **Do** reveal each section once with a 28px rise, fade and 6px blur on cubic-bezier(0.16, 1, 0.3, 1), visible by default and fully off under reduced motion.

### Don't:
- **Don't** use cyan outside the bar passage and the bar's own service plate.
- **Don't** fill sections, cards or large surfaces with gold.
- **Don't** center a headline over rows of identical icon cards, or put photos in small thumbnail boxes; photos are full-bleed or tall plates.
- **Don't** use a cream or light ground; this world is night.
- **Don't** set buttons, fields or labels in Playfair Display.
- **Don't** use hard offset shadows; shadows are glow or soft float.
- **Don't** use WhatsApp's green outside the elements that depict WhatsApp.
