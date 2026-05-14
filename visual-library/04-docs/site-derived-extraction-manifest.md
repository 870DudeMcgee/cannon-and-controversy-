# Site-Derived Extraction Manifest

This is the concrete extraction pass from the live site into the `site-derived/` folders.

## Pull From Stylesheet Tokens

Source area:
- [index.html](index.html#L13)

Extract:
- palette swatches for `bg`, `bg-deep`, `bg-card`, `bg-parch`, `gold`, `gold-lt`, `gold-dim`, `red`, `text`, `text-muted`, `rule-gold`

Destination:
- `typography-references/site-derived/`
- `scroll-textures/site-derived/`

Derived outputs:
- color reference sheet
- texture grade reference sheet

## Pull From Section Heading System

Source area:
- [index.html](index.html#L210)

Extract:
- `part-num` small-cap hierarchy
- `h2` title spacing and color ratios
- `heading-rule` line lengths and ornament balance

Destination:
- `typography-references/site-derived/`

Derived outputs:
- chapter heading sheet
- ornament spacing guide

## Pull From Callout Panels

Source area:
- [index.html](index.html#L299)

Extract:
- parchment panel color and noise
- centered top sigil treatment
- red label style
- text rhythm inside the panel

Destination:
- `scroll-textures/site-derived/`
- `typography-references/site-derived/`

Derived outputs:
- quote card background
- callout header style
- parchment panel still

## Pull From Pull Quote System

Source area:
- [index.html](index.html#L349)

Extract:
- left gold rule weight
- drop quote glyph proportion
- IM Fell quote styling
- citation line treatment

Destination:
- `typography-references/site-derived/`

Derived outputs:
- witness quote template
- pull quote typography board

## Pull From Timeline System

Source area:
- [index.html](index.html#L390)
- [index.html](index.html#L967)

Extract:
- year column width and weight
- dot marker ratio
- illuminated gradient spine
- miniature medallion proportions
- source note styling under entries

Destination:
- `maps/site-derived/`
- `typography-references/site-derived/`
- `manuscripts/site-derived/`

Derived outputs:
- timeline marker pack
- timeline typography guide
- event card components

## Pull From Fact Bar

Source area:
- [index.html](index.html#L644)

Extract:
- oversized numeral treatment
- muted caption logic
- dark card block spacing
- gold/rule contrast values

Destination:
- `typography-references/site-derived/`

Derived outputs:
- stat card system
- date impact card

## Pull From Codex Hero

Source area:
- [index.html](index.html#L802)
- [index.html](index.html#L1220)

Extract:
- page silhouette
- inset red/green frame rings
- miniature aperture proportions
- vertical caption treatment
- Ge'ez footer band impression

Destination:
- `manuscripts/site-derived/`
- `ethiopian-art/site-derived/`

Derived outputs:
- codex silhouette png or svg
- codex frame plate
- miniature window reference

## Pull From Section Plate

Source area:
- [index.html](index.html#L875)

Extract:
- parchment slab gradient
- double frame system
- lower-right ornament signature
- kicker/title/note hierarchy

Destination:
- `ethiopian-art/site-derived/`
- `typography-references/site-derived/`
- `scroll-textures/site-derived/`

Derived outputs:
- chapter intro plate
- title block reference
- ornament corner pack

## Pull From Divider System

Source area:
- [index.html](index.html#L616)

Extract:
- line fade logic
- center glyph rhythm
- spacing between line and glyph cluster

Destination:
- `typography-references/site-derived/`

Derived outputs:
- divider pack
- lower-third separator

## Immediate Folder Drops

### manuscripts/site-derived
- codex silhouette still
- codex window crop
- hero miniature frame reference

### scroll-textures/site-derived
- archival background texture
- parchment callout panel still
- section plate parchment slab

### ethiopian-art/site-derived
- codex frame ring reference
- miniature-inspired ornament strip
- section plate corner ornament

### typography-references/site-derived
- heading hierarchy sheet
- pull quote layout board
- fact-bar number system
- divider spacing board
- timeline year and source label system

### maps/site-derived
- timeline medallion proportions
- illuminated spine reference
- date marker proportions

## Build Order

1. Export the color and heading references.
2. Export the callout and section plate stills.
3. Export codex and timeline component references.
4. Convert the strongest references into reusable SVG templates.
