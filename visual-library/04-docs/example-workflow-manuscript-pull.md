# Example Workflow: Manuscript Pull

This is a narrow workflow for collecting manuscript material without getting dragged into the full archive.

Goal: collect a small manuscript batch that supports codex transitions, quote reveals, chapter intros, and illuminated border language.

## Step 1: Open The Right Surfaces

Open these first:

- `visual-library/index.html`
- `visual-library/style-board.html`
- `visual-library/folder-map.html`
- `visual-library/04-docs/signature-motif-bible.md`
- `visual-library/04-docs/asset-tracker.csv`

Why:
- the style board shows the right parchment and codex atmosphere
- the motif bible keeps the search tied to recurring series language
- the folder map reminds you where manuscript assets belong
- the tracker keeps the batch accountable

## Step 2: Choose One Tight Manuscript Batch

Do not search for "all biblical manuscripts."

Pick one of these instead:
- rubricated pages with gold initials
- open codex spreads
- gospel book leaves
- illuminated canon tables
- uncial or ornamental lettering references

Good batch size:
- 5 assets minimum
- 10 assets maximum

## Step 3: Start From Existing Planned Targets

Use the seeded rows that are already aligned to the system.

Good starting rows:
- `pending-manuscripts-rubricated-page-001`
- `pending-manuscripts-codex-spread-001`
- `pending-manuscripts-canon-tables-001`
- `pending-manuscripts-leaf-gospel-book-001`
- `pending-manuscripts-gospel-decorated-001`
- `pending-manuscripts-open-bible-page-001`
- `pending-typography-uncial-page-001`
- `pending-typography-illuminated-initial-001`

These are already aimed at the codex, border, and red/gold motifs.

## Step 4: Save Into The Right Collection

Use these destinations:

- manuscript leaves and codex spreads -> `visual-library/01-core-collections/manuscripts/raw/`
- lettering references -> `visual-library/01-core-collections/typography-references/raw/`
- parchment textures extracted from manuscript scans -> `visual-library/01-core-collections/scroll-textures/raw/`

If a file is still unsorted, place it in `visual-library/03-ingest/` and sort it after the batch is complete.

## Step 5: Judge The Assets Against The Motifs

Keep an asset if it helps one of these:
- codex-opening transition
- glowing parchment reveal
- illuminated borders
- red/gold text reveals
- chapter intro atmosphere

Reject an asset if:
- the page is too damaged to read as intentional
- the lighting feels too modern or clinical
- the page is visually flat and offers no ornament, texture, or hierarchy
- the source or licensing is unclear

## Step 6: Connect It To Existing Kit Pieces

These current assets are the benchmark for what belongs:

- `02-series-kits/episode-neutral/codex-opening-plate-01.svg`
- `02-series-kits/episode-neutral/parchment-reveal-plate-01.svg`
- `02-series-kits/episode-neutral/chapter-intro-plate-01.svg`
- `02-series-kits/frame-elements/illuminated-border-01.svg`
- `02-series-kits/frame-elements/illuminated-border-02.svg`
- `02-series-kits/frame-elements/gold-rule-01.svg`

If the new asset would strengthen one of those systems, it belongs.

## Step 7: Log Immediately

For each useful file, update `asset-tracker.csv` with:
- the working or final filename
- source institution
- URL
- license status
- orientation
- notes about motif support

Do not defer metadata.

## Step 8: Promote The Best Ones

After the batch is done:
- move the strongest 2 to 4 manuscript images into `curated/`
- keep supporting scans and alternates in `raw/`
- move any extracted texture-like material into overlays only if it is clearly reusable as atmosphere

## What Success Looks Like

A good manuscript session looks like this:
- 5 to 10 files collected
- all stored in the right category
- all logged
- at least 2 assets clearly usable for codex, parchment, or border systems

That is enough progress for one sitting.
