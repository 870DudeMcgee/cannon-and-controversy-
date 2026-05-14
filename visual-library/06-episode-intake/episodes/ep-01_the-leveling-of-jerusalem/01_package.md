# 01 Package: Episode 01

- episode title: The Leveling of Jerusalem
- episode code: ep-01_the-leveling-of-jerusalem
- narrative focus: The forty-year fuse from the crucifixion to the destruction of Jerusalem and the post-Temple canon consequences.
- source review status: source narrative locked for first assembly from site research
- visual review status: reusable system ready; final selected title cards, lower thirds, quote cards, evidence cards, and end-card wording locked in `05_assets_text.md`
- owner: Jewel Bait

## Approved Inputs

- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-01.svg`
  - why it belongs: strongest reusable opener/title surface for the episode's central title beat
  - bucket: `01-opener`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-02.svg`
  - why it belongs: alternate chapter-break plate for internal section shifts
  - bucket: `07-chapter-breaks`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/quote-card-template-01.svg`
  - why it belongs: base surface for Josephus and Caiaphas witness cards
  - bucket: `03-quote-witness`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/source-citation-card-01.svg`
  - why it belongs: source attribution and end-of-section evidence card
  - bucket: `08-outro`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/locator-badge-jerusalem.svg`
  - why it belongs: anchor mark for Jerusalem map orientation
  - bucket: `04-map-sequence`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/map-marker-01.svg`
  - why it belongs: recurring destination marker for Jerusalem and Rome-facing route studies
  - bucket: `04-map-sequence`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/timeline-spine-overlay-01.svg`
  - why it belongs: best bridge between the forty-year chain table and motion timeline language
  - bucket: `05-canon-conflict`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/dust-field-01.svg`
  - why it belongs: low-cost atmosphere overlay for ruin, ash, and aftermath beats
  - bucket: `06-transition-atmosphere`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/glow-veil-01.svg`
  - why it belongs: supports parchment reveal transitions and controlled title emphasis
  - bucket: `06-transition-atmosphere`
  - reusable or episode-specific: reusable
- `visual-library/05-ai-automation/briefs/jerusalem-map-sequence-brief.json`
  - why it belongs: already scoped to the episode's geography and recurring map needs
  - bucket: `04-map-sequence`
  - reusable or episode-specific: episode-specific first use, reusable after proving itself
- `visual-library/05-ai-automation/runs/2026-05-14_jerusalem-map-run_starter_v001.md`
  - why it belongs: starter provenance file for the episode's main map-generation pass
  - bucket: `04-map-sequence`
  - reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/prompt-packs/episode-01/ep-01_titles-forty-year-fuse-prompt.md`
  - why it belongs: converts the site's own headings into usable chapter-title and opener copy variants
  - bucket: `01-opener`
  - reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/prompt-packs/episode-01/ep-01_quote-cards-josephus-caiaphas-prompt.md`
  - why it belongs: converts the site's strongest quotations into on-screen quote/source card variants
  - bucket: `03-quote-witness`
  - reusable or episode-specific: episode-specific
- `visual-library/06-episode-intake/episodes/ep-01_the-leveling-of-jerusalem/05_assets_text.md`
  - why it belongs: turns the approved Episode 01 subjects into usable on-screen identifiers for the first cut
  - bucket: `03-quote-witness`
  - reusable or episode-specific: episode-specific
- `visual-library/06-episode-intake/episodes/ep-01_the-leveling-of-jerusalem/04_visual_beats.md`
  - why it belongs: gives the first assembly a beat-by-beat editorial order with narration and screen-text placements
  - bucket: `01-opener`
  - reusable or episode-specific: episode-specific
- `visual-library/06-episode-intake/episodes/ep-01_the-leveling-of-jerusalem/03_script.md`
  - why it belongs: provides a practice-ready spoken draft aligned to the episode's existing beat structure
  - bucket: `01-opener`
  - reusable or episode-specific: episode-specific
- `visual-library/06-episode-intake/episodes/ep-01_the-leveling-of-jerusalem/05_assets_text.md`
  - why it belongs: locks Caiaphas and Josephus into final first-cut quote-card wording and source captions
  - bucket: `03-quote-witness`
  - reusable or episode-specific: episode-specific

## Shot Buckets

- `01-opener`:
  - cold open title built from `chapter-intro-plate-01.svg`
  - text generated from `ep-01_titles-forty-year-fuse-prompt.md`
  - optional ash/parchment transition support from `glow-veil-01.svg`
- `02-historical-context`:
  - site-derived narration spine from the section `The Crucifixion and the Road to 70 AD`
  - manuscript atmosphere plate generation pass recommended from `manuscript-atmosphere-plates-brief.json`
- `03-quote-witness`:
  - Josephus pull quote card
  - Caiaphas political-calculation card from John 11:49–50
  - base surfaces: `quote-card-template-01.svg` and `source-citation-card-01.svg`
- `04-map-sequence`:
  - Jerusalem orientation map sequence
  - route/tension study between Jerusalem, Judea, and Rome-facing diaspora fracture points
  - primary assets: `locator-badge-jerusalem.svg`, `map-marker-01.svg`, `jerusalem-map-sequence-brief.json`, `2026-05-14_jerusalem-map-run_starter_v001.md`
- `05-canon-conflict`:
  - timeline of ~30 AD, 49 AD, 62 AD, 66 AD, 70 AD, and ~85–100 AD
  - primary visual support from `timeline-spine-overlay-01.svg`
  - chapter text should emphasize the line from Temple collapse to Yavneh/Jamnia consolidation
- `06-transition-atmosphere`:
  - ash, dust, parchment, and ruin transitions
  - use `dust-field-01.svg`, `glow-veil-01.svg`, and future manuscript atmosphere plates
- `07-chapter-breaks`:
  - use `chapter-intro-plate-02.svg` for section shifts such as `The Fire That Would Not Die` and `The Death That Cracked the Dam`
- `08-outro`:
  - source-citation close on the consequence line that the Bible split is born through process rather than one meeting
  - use `source-citation-card-01.svg`

## Missing Pieces

- what still needs sourcing:
  - optional public-domain visual sourcing can continue without blocking the first cut
- what still needs generation:
  - none at the text layer for the first assembly
- what still needs text population:
  - final title cards, lower thirds, quote cards, evidence cards, and end-card wording are locked in `05_assets_text.md`

## Notes

This episode should lead with political pressure, not abstract theology. The visual language should move from crucifixion warning, to escalating pressure, to Jerusalem's collapse, to the canon consequences that follow from the Temple's destruction. Use `04_visual_beats.md` as the working order for the first assembly, `05_assets_text.md` as the default on-screen text sheet, and `03_script.md` for spoken rehearsal.
