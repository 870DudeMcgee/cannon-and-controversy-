# Episode Production Roadmap

Use this roadmap every time a new episode package is created. The goal is to prevent drift between planning files, writing files, and on-screen text files.

This roadmap applies to all new episodes going forward.

Legacy episodes may keep the older split filenames, but every new episode should use the numbered six-file standard below.

## Completion Standard

An episode is not complete until it contains all of the following:

- `01_package.md`
- `02_production.md`
- `03_script.md`
- `04_visual_beats.md`
- `05_assets_text.md`
- `06_shot_bucket.csv`
- the eight standard bucket folders

For new episodes, `05_assets_text.md` is the single on-screen text file. It combines lower thirds, quote cards, evidence strips, comparison notes, and source-strip wording so the editor does not need to chase multiple files.

## Build Order

Create episodes in this order:

1. Create the folder and the eight standard bucket folders.
2. Draft `01_package.md`.
3. Draft `02_production.md`.
4. Draft `06_shot_bucket.csv`.
5. Draft `03_script.md`.
6. Draft `05_assets_text.md`.
7. Draft `04_visual_beats.md` only after the production file, script, and assets text are stable enough to map shot order to narration beats.
8. Validate the folder against the checklist below.

## File Roles

- `01_package.md`:
  - high-level plan, asset logic, missing pieces, and episode-level notes
- `02_production.md`:
  - act structure, shot order, generation priorities, editing rules, and first-assembly instructions
- `03_script.md`:
  - spoken script aligned to the production order
- `04_visual_beats.md`:
  - beat-by-beat assembly guide tying visuals, narration, screen text, and notes into one first-cut sequence
- `05_assets_text.md`:
  - lower thirds, quote cards, evidence strips, comparison language, and source-strip labels used as the main first-cut text surface
- `06_shot_bucket.csv`:
  - asset tracking and next actions by bucket

## Legacy Mapping

If you are converting from the older split-file system, use this mapping:

- `episode-package.md` -> `01_package.md`
- `production-packet.md` -> `02_production.md`
- `narration-draft.md` -> `03_script.md`
- `edit-script.md` -> `04_visual_beats.md`
- `lower-third-copy.md` + `quote-card-copy.md` + `evidence-card-copy.md` + `comparison-card-copy.md` -> `05_assets_text.md`
- `shot-bucket.csv` -> `06_shot_bucket.csv`

## Packet Wiring Rules

Before marking an episode complete, confirm these references exist:

- `02_production.md` must mention `05_assets_text.md` as the default first-assembly text sheet.
- `02_production.md` must mention `04_visual_beats.md` as the first-pass cut order.
- `03_script.md` must list `04_visual_beats.md` in its `use with` line.
- `01_package.md` should identify `05_assets_text.md` as the default first-cut text sheet and point to `04_visual_beats.md` as the working assembly order.
- `04_visual_beats.md` should reference `05_assets_text.md` wherever the cut depends on screen text.

## Validation Checklist

Run this check before exposing the episode in intake or automation surfaces:

1. The folder contains all required files.
2. `02_production.md` and `04_visual_beats.md` describe the same assembly order.
3. `03_script.md` beats align with the visual-beats flow.
4. `05_assets_text.md` covers every named person, place, text, institution, quote, and evidence strip that appears in the first cut.
5. `06_shot_bucket.csv` points to the actual first-cut surfaces used in the edit.

## Fast Gap Check

If an episode feels incomplete, check these in order:

1. Is `04_visual_beats.md` missing?
2. Is `05_assets_text.md` missing or too thin?
3. Does `05_assets_text.md` fail to cover one of the core evidence sections?
4. Does `02_production.md` fail to mention the visual beats or assets text files?
5. Does the `03_script.md` `use with` line omit the assembly files the editor actually needs?

## Assets Text Guidance

Inside `05_assets_text.md`, use clear sections such as:

- lower thirds
- quote cards
- evidence strips
- comparison cards
- source strips
- end-card lines