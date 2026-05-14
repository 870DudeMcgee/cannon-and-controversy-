# 01 Package: Episode 08

- episode title: The Removed Books: What They Are
- episode code: ep-08_the-removed-books-what-they-are
- narrative focus: Episode 08 turns from consequence to inventory. It identifies the seven deuterocanonical books and the Greek additions to Esther and Daniel, showing what each text contributes and why these books are concrete works rather than a vague missing category.
- source review status: source narrative locked for first assembly from the removed-books section and the additions-to-existing-books section
- visual review status: reusable system ready; final selected title cards, lower thirds, quote cards, evidence cards, comparison cards, and end-card wording locked in `05_assets_text.md`
- owner: Jewel Bait

## Approved Inputs

- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-01.svg`
	- why it belongs: strongest reusable opener surface for the excluded-not-erased framing of the removed books
	- bucket: `01-opener`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/chapter-intro-plate-02.svg`
	- why it belongs: clean chapter-break surface for the seven-book survey, the historical and wisdom clusters, and the additions section
	- bucket: `07-chapter-breaks`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/quote-card-template-01.svg`
	- why it belongs: best reusable base for book-profile cards and short feature cards
	- bucket: `03-quote-witness`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/episode-neutral/source-citation-card-01.svg`
	- why it belongs: strongest closing surface for the excluded-not-erased end-card
	- bucket: `08-outro`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/timeline-spine-overlay-01.svg`
	- why it belongs: supports a concise sequence showing where these books sit between prophecy, Maccabees, Alexandria, and later exclusion
	- bucket: `05-canon-conflict`
	- reusable or episode-specific: reusable
- `visual-library/02-series-kits/frame-elements/glow-veil-01.svg`
	- why it belongs: controlled reveal layer for profile cards and additions transitions
	- bucket: `06-transition-atmosphere`
	- reusable or episode-specific: reusable
- `visual-library/05-ai-automation/prompt-packs/episode-08/ep-08_titles-removed-books-prompt.md`
	- why it belongs: turns the removed-books section into opener and chapter-title variants
	- bucket: `01-opener`
	- reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/prompt-packs/episode-08/ep-08_book-profile-cards-prompt.md`
	- why it belongs: generates the seven book-profile cards plus the Esther and Daniel additions cards needed for the first cut
	- bucket: `03-quote-witness`
	- reusable or episode-specific: episode-specific
- `visual-library/05-ai-automation/briefs/manuscript-atmosphere-plates-brief.json`
	- why it belongs: supports codex, parchment, and library-shelf atmosphere for a guided inventory episode
	- bucket: `02-historical-context`
	- reusable or episode-specific: reusable first use

## Shot Buckets

- `01-opener`:
	- cold open title built from `chapter-intro-plate-01.svg`
	- opener lines generated from `ep-08_titles-removed-books-prompt.md`
	- the opening claim should establish that these books are excluded, not erased
- `02-historical-context`:
	- site-derived narration spine from `The Removed Books: What They Are`
	- codex and library atmosphere beds from the manuscript prompt brief
- `03-quote-witness`:
	- Tobit and Judith profile cards
	- 1 and 2 Maccabees profile cards
	- Wisdom, Sirach, and Baruch profile cards
	- additions-to-Esther and Daniel comparison cards
	- final excluded-not-erased end-card
- `04-map-sequence`:
	- not geographical in the standard sense
	- use only if a simple Alexandria Jerusalem Babylon and Maccabean-era locator card helps orient settings
- `05-canon-conflict`:
	- quick sequence showing how these books sit inside the wider canon history and later exclusion
	- synthesis card on what each book contributes that later readers lose direct access to
- `06-transition-atmosphere`:
	- parchment, codex, margin, and shelf transitions
	- use `glow-veil-01.svg` with restraint
- `07-chapter-breaks`:
	- use `chapter-intro-plate-02.svg` for shifts between narrative books, wisdom/history books, and additions to existing books
- `08-outro`:
	- end on the line that these books were excluded from one tradition, not lost to history
	- use `source-citation-card-01.svg`

## Missing Pieces

- what still needs sourcing:
	- optional public-domain visual sourcing can continue without blocking the first cut
- what still needs generation:
	- none at the text layer for the first assembly
- what still needs text population:
	- final title cards, lower thirds, quote cards, evidence cards, comparison cards, and end-card wording are locked in `05_assets_text.md`

## Notes

This episode should work as a guided inventory, not a detached appendix. The point is to make the removed books concrete and memorable after the consequence-heavy Episodes 06 and 07.

Use `04_visual_beats.md` as the working order for the first assembly, `03_script.md` as the spoken rehearsal script, and `05_assets_text.md` as the default first-cut sheet for book-profile cards, identifiers, and end-card lines.