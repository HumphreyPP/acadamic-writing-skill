# Academic Writing

`academic-writing` is a focused repository for Codex skills that support research writing.

This repository is meant to hold reusable writing skills, shared guidance, and lightweight checklists for:

- literature reviews
- methodology sections
- data analysis writing
- theory dialogue and conceptual contribution writing

## Scope

Keep this repository narrow.

Include:

- skill folders that Codex can invoke directly
- shared references used across multiple skills
- short checklists or rubrics that improve writing consistency

Do not include:

- raw paper PDFs
- large datasets
- project-specific manuscript drafts
- temporary exports or unrelated research artifacts

## Structure

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

- `literature-review-writing`: Write evidence-led review prose with sentence-level citation discipline and explicit control over AI-sounding patterns.
- `methodology-writing`: Explain design choices, operationalization, procedures, and validity logic without sliding into template language.
- `data-analysis-writing`: Turn analytic results into precise prose that separates pattern description, directional findings, and interpretation.
- `theory-dialogue-writing`: Write paragraphs that actively converse with theory instead of merely restating empirical results.

## Usage

Invoke a skill directly in Codex with prompts such as:

- `Use $literature-review-writing to draft a review paragraph on ...`
- `Use $methodology-writing to revise the methods section for ...`
- `Use $data-analysis-writing to write the results narrative for ...`
- `Use $theory-dialogue-writing to strengthen the conceptual contribution in ...`

## Maintenance Notes

- Keep shared norms in `shared/references/` when multiple skills need them.
- Keep skill-specific operating rules inside each skill folder.
- Prefer small, inspectable updates over large mixed commits.
