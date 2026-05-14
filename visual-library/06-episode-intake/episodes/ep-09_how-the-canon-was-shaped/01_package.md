# 01 Package: Episode 09

- episode title: How the Canon Was Shaped
- episode code: ep-09_how-the-canon-was-shaped
- narrative focus: Episode 09 closes the series by turning the canon debate into a chronology viewers can retain. It shows that the canon was formed across centuries through Jewish consolidation, Christian witness, councils, translators, reformers, and print-distribution decisions.
- source review status: core textual spine established from `The Timeline: How the Canon Was Shaped`
- visual review status: reusable system ready; episode-specific timeline cards and witness cards still need first-pass generation
- owner: Jewel Bait

## Approved Inputs

- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-01.svg`
	- why it belongs: strongest reusable opener surface for the series-finale chronology claim
	- bucket: `01-opener`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-02.svg`
	- why it belongs: clean chapter-break surface for early formation, patristic and conciliar decisions, and Reformation closure
	- bucket: `07-chapter-breaks`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/quote-card-template-01.svg`
	- why it belongs: best reusable base for witness cards, milestone cards, and disputed-canon quotations
	- bucket: `03-quote-witness`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/source-citation-card-01.svg`
	- why it belongs: strongest closing surface for the final centuries-long canon conclusion
	- bucket: `08-outro`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/timeline-spine-overlay-01.svg`
	- why it belongs: central visual spine for the chronology from Septuagint to Bible Society cutoff
	- bucket: `05-canon-conflict`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/glow-veil-01.svg`
	- why it belongs: controlled reveal layer for transitions between chronology clusters
	- bucket: `06-transition-atmosphere`
	- reusable or episode-specific: reusable
- `visual-library/05-ai-automation/prompt-packs/episode-09/ep-09_titles-canon-timeline-prompt.md`
	- why it belongs: turns the site timeline into opener and chapter-title variants for the finale
	- bucket: `01-opener`
	- reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/prompt-packs/episode-09/ep-09_timeline-cards-prompt.md`
	- why it belongs: generates milestone cards, witness cards, chronology strips, and finale end-cards for the timeline episode
	- bucket: `03-quote-witness`
	- reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/briefs/manuscript-atmosphere-plates-brief.json`
	- why it belongs: supports the archive, council, codex, and print-history atmosphere for a long-range chronology episode
	- bucket: `02-historical-context`
	- reusable or episode-specific: reusable first use

## Shot Buckets

- `01-opener`:
	- cold open title built from `chapter-intro-plate-01.svg`
	- opener lines generated from `ep-09_titles-canon-timeline-prompt.md`
	- the opening claim should establish that the canon was shaped over centuries, not fixed in one moment
- `02-historical-context`:
	- site-derived narration spine from `The Timeline: How the Canon Was Shaped`
	- archive, codex, and council atmosphere beds from the manuscript prompt brief
- `03-quote-witness`:
	- Yavneh process card
	- Irenaeus, Origen, Athanasius, and Jerome witness cards
	- Luther preface and Westminster rejection cards
	- final chronology synthesis card
- `04-map-sequence`:
	- use only if a sparse geography card helps connect Alexandria, Rome, North Africa, Wittenberg, and London print culture
	- do not let geography compete with chronology
- `05-canon-conflict`:
	- full timeline spine from Palestinian canon closure to 1826 Bible Society cutoff
	- synthesis card showing how each decision changed what later Christians read
- `06-transition-atmosphere`:
	- ash, codex, council, and print-shop transitions
	- use `glow-veil-01.svg` with restraint
- `07-chapter-breaks`:
	- use `chapter-intro-plate-02.svg` for shifts between early formation, patristic uncertainty, conciliar standardization, and Reformation closure
- `08-outro`:
	- end on the line that the canon was shaped by a chain of decisions across centuries
	- use `source-citation-card-01.svg`

## Missing Pieces

- what still needs sourcing:
	- one or two public-domain council, codex, or print-era visuals suited to the later chronology beats
	- optional public-domain engraving or press imagery for the nineteenth-century Bible Society cutoff
- what still needs generation:
	- title and chapter-card variants
	- milestone cards for the major canon events
	- witness cards for Irenaeus, Origen, Jerome, Luther, and Westminster
- what still needs text population:
	- final opener title variants
	- final short milestone wording for the major timeline stops
	- lower-third or source-strip identifiers for dates, councils, letters, and confessions

## Notes

This episode should feel like the closing chronology for the whole documentary block. It should gather the argument without reopening every dispute at full length.

Use `04_visual_beats.md` as the working order for the first assembly, `03_script.md` as the spoken rehearsal script, and `05_assets_text.md` as the default first-cut sheet for milestone cards, witness lines, and end-card text.