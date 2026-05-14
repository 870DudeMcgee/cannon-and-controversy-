# Batch: British Library

This batch focuses on manuscripts, Ethiopian ornament, and parchment detail. The goal is to feed codex openings, illuminated borders, and parchment reveal systems.

## Pull Targets

1. Search: `ethiopian gospel manuscript folio`
   Category: manuscripts
   Tracker row: `pending-manuscripts-ethiopian-gospel-001`
   Keep if: border geometry is crop-friendly and parchment texture is strong

2. Search: `illuminated gospel incipit page`
   Category: manuscripts
   Tracker row: `pending-manuscripts-incipit-page-001`
   Keep if: title-page hierarchy is strong enough for chapter cards

3. Search: `rubricated manuscript page gold initial`
   Category: manuscripts
   Tracker row: add after first hit
   Keep if: red/gold interplay is strong under dark grading

4. Search: `uncial manuscript script page`
   Category: typography-references
   Tracker row: add after first hit
   Keep if: lettering can influence lower thirds or date cards

5. Search: `ethiopian manuscript illumination saint`
   Category: ethiopian-art
   Tracker row: add after first hit
   Keep if: miniature fragments can be isolated cleanly

6. Search: `vellum codex open spread`
   Category: manuscripts
   Tracker row: add after first hit
   Keep if: page turn or spread geometry can anchor a codex-opening sequence

7. Search: `parchment manuscript edge detail`
   Category: scroll-textures
   Tracker row: `pending-scroll-textures-edge-detail-001`
   Keep if: edge wear can become overlays or masks

8. Search: `medieval illuminated initial letter`
   Category: typography-references
   Tracker row: add after first hit
   Keep if: initials can become reusable chapter ornaments

9. Search: `gospel canon tables manuscript`
   Category: manuscripts
   Tracker row: add after first hit
   Keep if: symmetry and ornament feel ceremonial enough for title cards

10. Search: `geez manuscript ornament border`
    Category: ethiopian-art
    Tracker row: `pending-ethiopian-art-border-001`
    Keep if: border modules can be excerpted into frame elements

## Batch Output Goal

- 25 raw assets
- 8 curated assets
- 4 border or miniature cutouts
- 3 parchment edge overlays

## Naming Shortcut

Use:
`british-library_subject_period_style_v001.ext`

## Stop Rule

If a candidate is historically interesting but visually weak, keep it out of `curated/`.
