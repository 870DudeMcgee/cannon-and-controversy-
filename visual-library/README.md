# Visual Library

This library is for the whole documentary series, not a single episode.

The goal is to build a reusable cinematic vocabulary from the visual language already present on the site: codex forms, parchment surfaces, Ethiopian manuscript influence, gold rulework, red accents, dark archival atmospheres, timeline structures, and Roman-to-Jerusalem historical geography.

## Structure

- `00-signature-motifs/`
  - Series-defining visual moves. These should recur across episodes until they become instantly recognizable.
- `01-core-collections/`
  - The main visual categories. Each category is split into:
    - `raw/`: everything collected before review
    - `curated/`: strongest approved assets
    - `cutouts/`: isolated subjects with transparent backgrounds or masks
    - `overlays/`: textures, grain, dust, borders, paper edges, glows
    - `site-derived/`: screenshots, crops, rebuilt textures, color references, and visual derivatives from the website
- `02-series-kits/`
  - Episode-neutral elements reused everywhere: frame elements, motion presets, title packages, overlays, and recurring layout devices.
- `03-ingest/`
  - Intake pipeline before assets are sorted and renamed.
- `04-docs/`
  - Strategy, sourcing, naming, and tracking.

## Naming

Use this pattern for every approved asset:

`category_subject_period_style_source_license_orientation_v001.ext`

Example:

`manuscripts_gospel-folio_14c_ethiopian_british-library_public-domain_portrait_v001.jpg`

## Collection Rules

- Prefer public-domain or clearly licensed assets first.
- Save source URL and license status immediately.
- Keep the best versions in `curated/`; never dump everything there.
- Put anything extracted from the website or remade from site motifs in `site-derived/`.
- Do not collect only literal historical images. Collect atmosphere, texture, framing, symbols, materials, and lighting that match the same world.
- Build for reuse: every asset should answer either `background`, `transition`, `overlay`, `cutaway`, `map sequence`, `timeline`, or `title treatment`.

## First Priority

Fill `00-signature-motifs/` and the `overlays/` plus `site-derived/` folders first. Those assets will create continuity across the entire series even before the episode-specific archive is complete.
