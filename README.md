# EDE 448 Positive Classroom Support Plan

This repository contains the editable LaTeX source and reference library for the Module 2 Positive Classroom Support Plan in **EDE 448: Communication and Positive Behavioral Supports for Students with Autism and Other Complex Needs**.

**Status:** Review draft. This repository is documentation and preparation; it is not evidence of submission to Blackboard.

## Assignment

- [Positive Classroom Support Plan](https://learn.rochester.edu/ultra/courses/_113760_1/outline/assessment/_9485975_1/overview?courseId=_113760_1)
- Due: July 31, 2026 at 11:59 PM EDT
- Requirement: describe a future positive classroom support plan using relevant Module 2 readings and media, with citations

## Files

- [`main.tex`](main.tex): complete journal-style paper and original TikZ diagrams
- [`references.bib`](references.bib): course, research, and camp-evidence references
- [`assets/identity-beads-evidence-still-life.png`](assets/identity-beads-evidence-still-life.png): public-safe conceptual visual used in the paper
- [`assets/README.md`](assets/README.md): visual provenance and use boundaries

## Paper Focus

The paper connects positive behavior support, accessible communication, positive self-talk, Productive Failure, and the EDU486 Identity Beads experience. It defines the Puzzle Plan and EQUITAS at first reader need and treats EQUITAS as the equity-centered heart of the Puzzle Plan.

The central distinction is that an unsuccessful attempt is an event and a source of evidence, not an identity or moral verdict. The paper also distinguishes ordinary difficulty and discomfort from language or conditions that threaten safety, dehumanize, or cause harm.

## Build

Compile with a LaTeX distribution that includes `latexmk`, `apacite`, and TikZ:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

Generated PDFs and LaTeX build files are intentionally ignored. Review the compiled PDF before any course submission.
