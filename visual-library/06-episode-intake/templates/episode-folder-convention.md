# Episode Folder Convention

Use this naming pattern for every new episode package:

`ep-XX_short-kebab-title`

Examples:
- `ep-01_the-leveling-of-jerusalem`
- `ep-02_the-first-bible-two-lists`
- `ep-03_luther-and-the-reformation-cut`

## Rules

- `ep-XX` is always two digits.
- Use lowercase letters only.
- Use hyphens between words after the numeric prefix.
- Keep the slug descriptive but short.
- The folder name should match the `episode code` inside the episode package file.

## Root File Naming Standard For New Episodes

For every new episode created from this point forward, use these exact root filenames inside the episode folder:

- `01_package.md`
- `02_production.md`
- `03_script.md`
- `04_visual_beats.md`
- `05_assets_text.md`
- `06_shot_bucket.csv`

This is the future-facing standard.

Episodes 01 through 05 have already been migrated to this numbered standard. If older notes mention the earlier split naming pattern, treat those names as historical references only and use the migration mapping in `episode-production-roadmap.md`.

## Minimum Required Files

Every episode package should contain:
- `01_package.md`
- `02_production.md`
- `03_script.md`
- `04_visual_beats.md`
- `05_assets_text.md`
- `06_shot_bucket.csv`
- the eight shot-bucket folders

## Consistency Rule

Every episode must reach the Episode 01 production standard before it is treated as complete.

- planning layer:
	- `01_package.md`
	- `02_production.md`
- assembly layer:
	- `04_visual_beats.md`
	- `06_shot_bucket.csv`
- performance layer:
	- `03_script.md`
- on-screen text layer:
	- `05_assets_text.md`
	- lower thirds, quote cards, evidence strips, comparison notes, and source strips should all live inside that one file

Use `episode-production-roadmap.md` as the checklist and sequencing guide for every new episode.

## Required Bucket Folders

- `01-opener/`
- `02-historical-context/`
- `03-quote-witness/`
- `04-map-sequence/`
- `05-canon-conflict/`
- `06-transition-atmosphere/`
- `07-chapter-breaks/`
- `08-outro/`

## Workflow Rule

Do not create custom bucket names unless a real production need forces it.
Default consistency is more valuable than clever folder naming.
