# 01 Package: Episode 02

- episode title: The First Bible: Two Different Lists
- episode code: ep-02_the-first-bible-two-lists
- narrative focus: Before Christianity fought over the canon, Jewish communities were already reading two different scriptural collections, and the later split inherits that earlier divergence.
- source review status: source narrative locked for first assembly from the Hebrew Bible and Septuagint section
- visual review status: reusable system ready; final selected title cards, lower thirds, quote cards, evidence cards, and end-card wording locked in `05_assets_text.md`
- owner: Jewel Bait

## Approved Inputs

- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-01.svg`
  - why it belongs: strongest reusable opener/title surface for the episode's central contrast beat
  - bucket: `01-opener`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-02.svg`
  - why it belongs: alternate chapter-break plate for moving between Palestine, Alexandria, and the consequence section
  - bucket: `07-chapter-breaks`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/quote-card-template-01.svg`
  - why it belongs: best reusable base for Josephus evidence cards and comparison callouts
  - bucket: `03-quote-witness`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/source-citation-card-01.svg`
  - why it belongs: best closing surface for the removal-not-addition evidence card
  - bucket: `08-outro`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/map-marker-01.svg`
  - why it belongs: supports a simple Jerusalem-to-Alexandria comparative geography beat
  - bucket: `04-map-sequence`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/timeline-spine-overlay-01.svg`
  - why it belongs: supports the long chronology from the Septuagint's early formation to later Christian adoption and Reformation removal
  - bucket: `05-canon-conflict`
  - reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/glow-veil-01.svg`
  - why it belongs: controlled parchment reveal for the opener and evidence transitions
  - bucket: `06-transition-atmosphere`
  - reusable or episode-specific: reusable
- `visual-library/05-ai-automation/prompt-packs/episode-02/ep-02_titles-two-lists-prompt.md`
  - why it belongs: turns the site's headings and claims into opener and chapter-title variants
  - bucket: `01-opener`
  - reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/prompt-packs/episode-02/ep-02_comparison-cards-hebrew-vs-septuagint-prompt.md`
  - why it belongs: generates the core Hebrew Bible vs Septuagint comparison cards and the final removal-not-addition evidence lines
  - bucket: `03-quote-witness`
  - reusable or episode-specific: episode-specific
- `visual-library/06-episode-intake/episodes/ep-02_the-first-bible-two-lists/03_script.md`
  - why it belongs: provides a practice-ready spoken draft aligned to the episode's comparison-first beat structure
  - bucket: `01-opener`
  - reusable or episode-specific: episode-specific
- `visual-library/06-episode-intake/episodes/ep-02_the-first-bible-two-lists/05_assets_text.md`
  - why it belongs: locks the Hebrew Bible, Septuagint, Josephus, and removed-not-added cards into first-cut wording
  - bucket: `03-quote-witness`
  - reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/briefs/manuscript-atmosphere-plates-brief.json`
  - why it belongs: supports parchment, codex, and scribal texture beds under the explanation-heavy sections
  - bucket: `02-historical-context`
  - reusable or episode-specific: reusable first use

## Shot Buckets

- `01-opener`:
  - cold open title built from `chapter-intro-plate-01.svg`
  - opener lines generated from `ep-02_titles-two-lists-prompt.md`
  - the opening claim should establish that the canon dispute starts before Christianity and should bridge directly out of Yavneh as the Episode 01 handoff
- `02-historical-context`:
  - site-derived narration spine from `What Is the Biblical Canon?` and `The First Bible: Two Different Lists`
  - parchment and codex atmosphere beds from the manuscript prompt brief
- `03-quote-witness`:
  - Josephus evidence card for the 22-book Hebrew collection
  - comparison cards for Hebrew Bible vs Septuagint
  - final evidence card for removed, not added
- `04-map-sequence`:
  - simple comparative geography between Palestine and Alexandria
  - use restrained labels rather than a complex route animation
- `05-canon-conflict`:
  - chronology from the Septuagint's early formation to early Christian adoption and the later Reformation cut
  - show inheritance before conflict
- `06-transition-atmosphere`:
  - parchment, codex, lamp-light, and scroll transitions
  - use `glow-veil-01.svg` with restraint
- `07-chapter-breaks`:
  - use `chapter-intro-plate-02.svg` for section shifts between Hebrew Bible, Septuagint, and consequence
- `08-outro`:
  - end on the line that the so-called removed books were removed from one tradition's Bible rather than added to another's
  - use `source-citation-card-01.svg`

## Missing Pieces

- what still needs sourcing:
  - optional public-domain visual sourcing can continue without blocking the first cut
- what still needs generation:
  - none at the text layer for the first assembly
- what still needs text population:
  - final title cards, lower thirds, quote cards, evidence cards, comparison cards, and end-card wording are locked in `05_assets_text.md`

## Notes

This episode should feel like a revelation of prehistory rather than a later church fight. The narrative job is to show that there was never one uncontested Old Testament list waiting in the background. Use comparison, geography, and inheritance language before escalation or controversy language.

The strongest bridge from Episode 01 is Yavneh: the surviving Pharisaic stream consolidates the Palestinian Hebrew collection after the Temple's fall, while early Christians continue reading from the broader Greek scriptures already in circulation. Josephus should be framed as a first-century witness giving a snapshot of that Hebrew collection during the same historical world as the apostles, not as a later detached commentator.

Use `04_visual_beats.md` as the working order for the first assembly, `03_script.md` as the spoken rehearsal script, and `05_assets_text.md` as the default first-cut sheet for identifiers, witness beats, and comparison wording.
