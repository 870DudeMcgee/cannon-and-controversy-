# AI Automation Layer

This folder turns the visual library into something that can be handed to other AI tools quickly.

The purpose is speed through reuse, not blind automation.

## Core Idea

Instead of re-explaining the whole documentary system every time, use a structured brief plus one task-specific prompt template.

That gives you:
- less repeated prompting
- more consistent style across tools
- easier delegation across image, video, and text workflows
- a paper trail for what was generated and why

## Folder Structure

- `briefs/`
  - Structured JSON templates and per-task copies.
- `prompts/`
  - Copy-ready prompt templates by output type.
- `runs/`
  - Logs, chosen prompts, notes, and final decisions from each AI-assisted run.

## Fast Workflow

1. Duplicate `briefs/master-job-brief-template.json` for the task.
2. Fill only the fields that matter.
3. Pick one prompt template from `prompts/`.
4. Paste the brief content into the AI tool with the prompt template.
5. Save the prompt version and results notes in `runs/`.
6. Review against the boards before moving anything into the actual library.

## Recommended Use Cases

### Image generation
Use for:
- style exploration
- atmosphere plates
- parchment backgrounds
- ornamental studies
- conceptual composites before manual finishing

Do not use it as a shortcut for historically specific artifacts unless you can verify them.

### Video generation
Use for:
- motion studies
- transitions
- slow push-ins
- parchment reveals
- map zoom mood tests

Treat these as prototypes unless accuracy and source requirements are clearly handled.

### Text generation
Use for:
- card copy variants
- source-card formatting
- chapter-title options
- research pull summaries
- shot-list first drafts

Always review for accuracy, tone, and overstatement.

## Rule For Approval

An AI-generated output does not belong in `curated/` or the reusable kits until it passes these checks:
- it fits the visual boards
- it supports a recurring motif or reusable need
- it does not introduce historical nonsense
- it has a documented source path or is clearly marked as generated

## Time-Saving Principle

Use AI to produce first passes and option sets.
Use the library to keep those first passes stylistically coherent.
Use human review to decide what survives.
