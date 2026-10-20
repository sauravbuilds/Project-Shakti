# Changelog — Project Shakti

A plain-English, dated log of structural decisions made to Project Shakti and why. Git already preserves every version of every file, this log exists to capture the reasoning behind changes, not just the diff.

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

## 2026-10-07 — Instagram added as a parallel layer, not nested under Report

Instagram documents the four pillars in real time for an external audience (the ICP and potential brand collaborations), it's forward-facing and event-driven (posted every 1-4 days, whenever something real happens). The Report is backward-facing and analytical, on a fixed cadence (monthly mandatory, weekly when possible), turning raw logs into decisions for personal use. These are different jobs, so Instagram sits alongside the Report as its own layer on top of the four pillars, documented separately in its own context file, rather than being nested inside Report.

## 2026-10-07 — Two new product-management folders: investing, nri-wealth-management

After the current PM challenge and the two MCP products, decided to go deeper into fintech domain expertise before starting the technical/AI-engineering curriculum, rather than in parallel with it. Reasoning: this directly compounds with the current job (an NRI wealth platform), the technical curriculum is mostly revision and lower urgency, and it keeps the Professional pillar active rather than going quiet once the PM challenge and MCPs are done. Added `investing/` (mutual funds and stock investing) and `nri-wealth-management/` (the specific problems NRIs face and how they're solved) under `product-management/`.

## 2026-10-07 — Numbered the product-management folders

`ai-engineering/` already has traceable order via its blocks; `product-management/` didn't. Added numeric prefixes reflecting the order each folder entered the plan: `01-mfd-exam/`, `02-concepts/`, `03-iim-case-studies/`, `04-product-teardowns/`, `05-investing/`, `06-nri-wealth-management/`. Folder renames, no content change.

## 2026-10-13 — Professional restructured into three legs: core-pm, tech-pm, gtm

The goal shifted from "PM who can also build agentic systems" to "PM who combines business sense, product judgment, AI system-design fluency, and go-to-market." Two problems with the old structure: `ai-engineering/` pulled toward software-engineering depth through its Block 1-6 curriculum, and GTM, which is daily work, had no place in the repo at all.

- Renamed `product-management/` to `01-core-pm/`. Contents and numbering unchanged.
- Replaced `ai-engineering/` (and its Block 1-6 curriculum) with `02-tech-pm/`, organized around what a PM needs: `01-evals/`, `02-ai-cost/`, `03-system-design/`, `04-builds/`. Builds stay, as the way to learn how these systems fail, but the framework-by-framework curriculum is gone.
- Added `03-gtm/`, a log of pricing, ICP, positioning, and channel decisions and lessons. Anonymized where needed, same rule as real work decisions.
- Updated the README, the folder READMEs, and the supporting context files to match.

## 2026-10-18 — Tech PM reorganized into nine topic folders

The first version of `02-tech-pm/` had four folders (`01-evals`, `02-ai-cost`, `03-system-design`, `04-builds`). Two problems: some folders were single concepts, not topic areas, and core topics like APIs had no home.

After researching what AI and technical PM roles expect, `02-tech-pm/` now has nine topic folders in learning order: `01-apis`, `02-llm-foundations`, `03-ai-architecture`, `04-evals-and-safety`, `05-ai-economics`, `06-data-and-sql`, `07-system-design`, `08-security-and-deployment`, `09-builds`.

- Folders are topic areas, never single concepts. Each concept becomes one file inside its folder, so nothing nests deeper.
- `01-apis` comes first because it's the base for everything else, and the research pointed to APIs, SQL, and system design as the technical core for a fintech PM.
- The AI concept folders come before system design, because HLD for AI systems pulls those pieces together.
- `04-product-teardowns` now records the publishing format: a Medium article, with the entry here holding the proof and links.

## 2026-10-20 — Core PM resequenced: NRI wealth management and investing before IIM case studies and teardowns

Day-job go-to-market work now needs real depth in the NRI wealth segment, so the domain folders moved ahead of the portfolio work. Order after the MFD exam: concepts, then NRI wealth management, then investing, then IIM case studies, then product teardowns. NRI comes before investing because the MFD exam already covers the mutual fund basics, and the NRI problems show what to learn in investing.

- `06-nri-wealth-management/` became `03-nri-wealth-management/`.
- `05-investing/` became `04-investing/`.
- `03-iim-case-studies/` became `05-iim-case-studies/`.
- `04-product-teardowns/` became `06-product-teardowns/`.

Folder renames only, no content change.