# Academic Writing

`academic-writing` is a focused repository of Codex skills for academic and research writing.

The repository is designed for reusable writing workflows rather than project storage. Its current focus is four common research-writing tasks:

- literature review writing
- methodology writing
- data analysis and results writing
- theory dialogue and conceptual contribution writing

## What This Repository Is For

Use this repository to store:

- skill folders that Codex can invoke directly
- shared references that multiple writing skills should reuse
- lightweight rubrics and checklists that improve writing consistency

Do not use this repository to store:

- raw paper PDFs
- large datasets
- manuscript drafts tied to one project
- temporary exports, notebooks, or unrelated research files

## Quick Start

Invoke a skill directly in Codex with prompts such as:

- `Use $literature-review-writing to draft a literature review paragraph on ...`
- `Use $methodology-writing to revise the methods section for ...`
- `Use $data-analysis-writing to turn these model outputs into a results narrative.`
- `Use $theory-dialogue-writing to strengthen the conceptual contribution in ...`

## Repository Structure

```text
academic-writing/
  README.md
  .gitignore
  shared/
    references/
  skills/
    literature-review-writing/
    methodology-writing/
    data-analysis-writing/
    theory-dialogue-writing/
```

## Current Skills

### `literature-review-writing`

Write evidence-led review prose with sentence-level citation discipline, lean parenthetical citations, and explicit control over AI-sounding phrasing.

### `methodology-writing`

Explain research design, operationalization, procedure, and rigor in prose that is specific, defensible, and not template-heavy.

### `data-analysis-writing`

Translate outputs, tables, or coded patterns into results prose that separates observation, direction, and interpretation.

### `theory-dialogue-writing`

Write paragraphs that actively engage theory by clarifying what empirical evidence refines, constrains, differentiates, or extends.

## Shared References

The `shared/references/` folder holds cross-skill norms that should stay consistent across the repository.

- `citation-discipline.md`: Align claims with citations and avoid citation stacking.
- `anti-ai-prose-checklist.md`: Remove repetitive sentence rhythm and template-heavy wording.
- `theory-dialogue-rubric.md`: Check whether a paragraph genuinely advances conceptual dialogue.

## Maintenance Principles

- Keep shared guidance in `shared/references/` when more than one skill needs it.
- Keep task-specific operating rules inside the relevant skill folder.
- Prefer revising an existing skill over creating overlapping near-duplicates.
- Keep commits narrow so later adjustments stay easy to inspect and reuse.
