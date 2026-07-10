# VisualCausal Probe Lab: Data visualization for Healey-Aligned Research

A professor-outreach research proposal aligned with **Christopher Healey** at **North Carolina State University**.

## For Professor Outreach

This repo is intended to support an honest outreach email. It contains a concrete proposal for what value you can add, but it does **not** yet contain completed experiments or results.

Start here:

- `outreach/value_add_packet.md` - professor-specific contribution plan.
- `outreach/email_draft.md` - short mail draft you can personalize before sending.
- `docs/one_page_project_plan.md` - one-page project summary.
- `PROJECT_STATUS.md` - clear statement of what exists and what does not exist yet.

## Research Question

How can a focused, reproducible artifact around **Data visualization** create useful research infrastructure for a lab working on **Data visualization, visual analytics, ML for visualization**?

## Advisor Fit

- **Professor:** Christopher Healey
- **University:** North Carolina State University
- **Program:** Computer Science PhD
- **CSV research area:** Data visualization, visual analytics, ML for visualization
- **Representative paper:** Attention and Visual Memory in Visualization and Computer Graphics; 2012; IEEE TVCG
- **Scholar link:** https://scholar.google.com/scholar?q=Attention+and+Visual+Memory+in+Visualization+and+Computer+Graphics

## Proposed Research-Grade Deliverable

Build **a robustness and failure-analysis benchmark for vision or vision-language models** with:

- A documented evaluation split with examples and source provenance.
- Baseline results for zero-shot, fine-tuned, and adapted models.
- Failure gallery with tags for viewpoint, object, context, annotation, and shortcut failures.
- A concise report identifying the highest-value next method to try.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `outreach/value_add_packet.md` - value-add plan for this professor.
- `outreach/email_draft.md` - email draft; personalize before sending.
- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/one_page_project_plan.md` - one-page project summary.
- `docs/experiment_plan.md` - baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Proposal scaffold only. Before external use, verify the professor's current lab page and make a selected repo public or shareable.
