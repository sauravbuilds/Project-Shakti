# Changelog — Project Shakti

A dated log of structural decisions made to Project Shakti and why. Git already preserves every version of every file, this log exists to capture the reasoning behind changes.

## 2026-10-03 — Previous changes (merged into one entry)

These changes happened before this changelog existed, so they're grouped here as one entry rather than dated individually.

- Finalized five pillars: Physical, Intellectual, Professional, Product, The Report.
- Renamed Technical → Professional. Reasoning: "Technical" implied engineering only and didn't fit product management work; Professional covers both as equal legs without subordinating either.
- Split Professional into `ai-engineering/` and `product-management/`.
- Renamed and repurposed the `automation/` folder into `product-management/` (no leftover content, clean rename).
- Decided `product-management/` subfolders: `mfd-exam/`, `concepts/`, `iim-case-studies/`, `product-teardowns/`. Each folder gets its own README at the topic level (not one for the pillar or category itself), so the structure stays visible on GitHub even when a folder is otherwise empty.
- Decided `product-teardowns/` covers both teardown and improvement work in one folder, without naming them as two separate project types.
- Added the baseline concept to the main README: every pillar starts from a documented baseline, progress is measured against it, not counted for its own sake.
- Repositioned the four pillar-adjacent quotes: "Start before you are ready" stays as opener; the Socrates body quote moved to sit right before the Five Pillars heading; "A moving man surely meets his luck" moved to The Report section; the Sanskrit shloka moved to the closing line.
- Removed em dashes throughout for cleaner prose.
- Reordered "How This Repository Gets Updated" to: Intellectual → Physical → Professional → Product → Report.

## 2026-10-03 — Instagram added as a parallel layer, not nested under Report

Instagram documents the four pillars in real time for an external audience- it's forward-facing and event-driven (posted every 1-4 days, whenever something real happens). The Report is backward-facing and analytical, on a fixed cadence (monthly mandatory, weekly when possible), turning raw logs into decisions for personal use. These are different jobs, so Instagram sits alongside the Report as its own layer on top of the four pillars, documented separately in its own context file, rather than being nested inside Report.
