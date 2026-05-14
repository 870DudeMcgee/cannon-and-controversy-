# Example Workflow: Jerusalem Map Pull

This is a single real use case that shows how to use the library without touching everything.

Goal: collect a small Jerusalem geography batch that supports future map zooms, route sequences, and Temple-context visuals.

## Step 1: Open The Right Surfaces

Open these first:

- `visual-library/index.html`
- `visual-library/map-board.html`
- `visual-library/folder-map.html`
- `visual-library/04-docs/asset-tracker.csv`

Why:
- the command center keeps navigation simple
- the map board shows the correct visual language
- the folder map reminds you where assets belong
- the tracker stops you from collecting untraceable files

## Step 2: Decide The Exact Batch

Do not search for "everything Jerusalem."

Search for one tight batch such as:
- ancient Jerusalem maps
- Temple illustrations or reconstructions
- Judea regional maps
- Jerusalem-to-Rome route references

Good batch size:
- 5 assets minimum
- 10 assets maximum

## Step 3: Use Existing Planned Targets

Start from the seeded tracker rows and pull list instead of inventing a new hunt.

Likely rows to convert first:
- `pending-maps-judea-palestine-001`
- `pending-temple-jerusalem-illustration-001`
- `pending-maps-nypl-jerusalem-001`
- `pending-maps-rumsey-environs-001`
- `pending-maps-rumsey-judaea-samaria-001`

These already point toward the right sources and keep the search narrow.

## Step 4: Save Into The Right Collection

Use these destinations:

- map images -> `visual-library/01-core-collections/maps/raw/`
- Temple visual references -> `visual-library/01-core-collections/temple-jerusalem/raw/`
- map textures or parchment map beds -> `visual-library/01-core-collections/maps/overlays/` only if they are clearly overlays

If you are not sure yet, place the files in `03-ingest/` first, then sort them in one pass.

## Step 5: Judge The Assets Against The Map Motif

Keep an asset if it helps with one of these:
- slow location zooms
- route line animation
- regional orientation
- Jerusalem context
- Temple context
- conflict-zone explanation

Reject an asset if:
- the geography is unclear
- the image is too modern-looking
- labels are unusable or too noisy
- the source or license is uncertain

## Step 6: Log Immediately

For each useful asset, update `asset-tracker.csv` with:
- final filename or placeholder name
- source institution
- source URL
- license status
- orientation
- notes about intended use

Do not leave this for later.

## Step 7: Promote The Best Ones

After the batch is collected:

- keep the strongest 2 to 4 in `curated/`
- move textures or atmospheric map beds into `overlays/` if appropriate
- leave weak or uncertain files in `raw/` until reviewed

## Step 8: Connect It Back To The System

Ask three final questions:

1. Would this look correct on `map-board.html`?
2. Does this help the `Map Zooms` motif from `signature-motif-bible.md`?
3. Could this appear in more than one episode?

If yes, it belongs in the long-term library.

## What Success Looks Like

A successful session is not "I searched all Jerusalem history."

A successful session is:
- 5 to 10 assets found
- each one stored in the right category
- each one logged
- at least 2 clearly reusable for future episodes

That is enough to build momentum without overload.
