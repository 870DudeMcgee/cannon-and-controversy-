# AI Media Generation Spec

- purpose: shared rules for generating documentary image assets from episode shopping lists
- use with: episode `08_media_shopping_list.md` files

## Core Rule

Generate background plates, illustration surfaces, comparison boards, and support visuals that can be dropped into a documentary timeline. Do not bake titles, lower thirds, captions, verse references, or logos into the image unless the shopping-list item explicitly asks for a text-ready board.

## Output Standard

- aspect ratio: 16:9
- target size: 3840x2160 when possible
- style: still-image documentary plate, not poster art
- texture level: restrained, historical, cinematic, readable
- text space: leave 35 to 45 percent clean negative space for overlays when the prompt asks for title, quote, or evidence usage
- color language: parchment, codex ivory, muted iron black, ash brown, dark red, old gold accents
- finish: subtle grain is fine; avoid hyper-sharp modern commercial polish

## Required Visual Direction

- historically grounded rather than fantasy-medieval
- solemn, investigative, text-friendly composition
- legible silhouettes and clear focal hierarchy
- avoid kitsch religious iconography unless the episode explicitly calls for it
- prefer archive, parchment, manuscript, stone, desert, candle, map, codex, and print-shop logic over abstract effects

## Avoid In Every Prompt

- no modern clothing
- no modern architecture
- no modern typography
- no visible watermarks
- no AI gibberish text
- no glowing fantasy magic effects
- no glossy blockbuster poster composition
- no exaggerated horror imagery
- no sermon-poster aesthetic

## File Naming Rule

Use this naming pattern when exporting generated assets:

- `ep-0X_item-slug_v01.png`
- examples:
  - `ep-01_jerusalem-locator-plate_v01.png`
  - `ep-05_jude-enoch-quote-board_v01.png`
  - `ep-09_print-cutoff-timeline_v01.png`

## Prompt Structure

Each shopping-list prompt should be treated as:

1. one deliverable or one tightly matched mini-set
2. one historical function inside the episode
3. one composition with enough negative space for documentary overlays

## Editing Rule

If a reusable series kit already covers the frame, border, or card container, generate only the interior image plate or background surface. Do not regenerate what already exists in `02-series-kits`.

## Public-Domain Sourcing Rule

When a shopping-list item calls for real historical material rather than invention, search public-domain collections first and generate only what is still missing.

Preferred sources:

- Wikimedia Commons
- Library of Congress
- New York Public Library Digital Collections
- Internet Archive
- The Metropolitan Museum of Art Collection
- Wellcome Collection

When searching:

- search for the underlying historical object, manuscript, map, engraving, excavation photo, or place image
- prefer high-resolution scans, engravings, manuscript plates, and archive photographs
- avoid low-resolution screenshots and unclear copyright status
- save the source URL and source title alongside the downloaded asset when possible