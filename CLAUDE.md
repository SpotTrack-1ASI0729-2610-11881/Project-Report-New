# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is **not** an application codebase. It is the written deliverable ("Informe del Trabajo Final") for the UPC course *Desarrollo de Aplicaciones Open Source* (1ASI0729), documenting the fictitious startup/product **SpotTrack** — an IoT-based platform for monitoring gym equipment usage and availability. There is no source code, package manager, build system, linter, or test suite here; the only "artifacts" are Markdown chapters, PlantUML diagrams, and exported PDFs/images.

The actual SpotTrack application lives in separate sibling repositories (referenced from `report/05-chapter5.md`), not in this repo:
- Frontend: `spottrack-webapp` (Angular)
- Backend: `spottrack-platform` (Spring Boot)
- Landing page: `spottrack-website`
- Mock API: `SpotTrack-Mock-Api`

When asked about the product's architecture, code, or bugs, look in those repos, not here — this repo only *documents* them.

## Repository structure

- **`README.md`** — the full report, rendered for GitHub viewing: cover page, version history, Student Outcome table, and all five chapters concatenated in one file.
- **`report/00-chapter0.md`** … **`report/05-chapter5.md`** — the same report split into per-chapter Markdown source files (0 = cover/front matter, I–V = the actual chapters). These are the pandoc source files used to produce the PDF/HTML exports (`chapters1-5.pdf`, `SpotTrack-Report.pdf`, `output.pdf`, `reporte.html`) via `header.tex` (LaTeX table-formatting tweaks) and `style.css` (HTML export styling).
- **`docs/c4/`, `docs/c4-frontend/`, `docs/c4-backend/`, `docs/c4-aggregate/`** — exported PNGs of C4 model diagrams (System Context, Containers, per-Bounded-Context views) embedded in the report.
- **`docs/class-diagrams-backend/`, `docs/class-diagrams-frontend/`** — `.puml` (PlantUML) source files for class diagrams, one per Bounded Context (e.g. `04_equipment_bc.puml`, `05_reservation_bc.puml`).
- **`assets/`** — all other images referenced by the report: team photos, interview evidence, wireframes/mockups/wireflows, style guide screenshots, deployment/CI evidence, etc.
- **`report/*.pdf`, `reporte.html`** — generated exports; do not hand-edit these, regenerate from the `.md` sources instead.

## Critical gotcha: two parallel copies of the report

`README.md` and `report/00-chapter0.md` through `report/05-chapter5.md` contain **the same content maintained in two places**. `README.md` is the GitHub-facing combined version; the `report/*.md` files are the pandoc source used to export PDFs. **When editing report content, update both** — the chapter files under `report/` and the corresponding section in `README.md` — or they will drift out of sync (this has happened before per the version history in the doc).

Relatedly, `README.md` uses `../assets/...` image paths throughout (correct for files living in `report/`, since `report/` is one level below root) but these paths are copied as-is into `README.md`, which sits at the repo root — so `../assets/...` there resolves *outside* the repository. Be aware of this when adding or fixing images in `README.md`; the working, root-relative form is `assets/...`.

## PlantUML diagrams

The `.puml` files under `docs/class-diagrams-backend/` and `docs/class-diagrams-frontend/` are not rendered locally. They are embedded in `report/04-chapter4.md` via the public PlantUML proxy, pointing at the raw file on GitHub, e.g.:
```
https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/05_reservation_bc.puml
```
This means edits to a `.puml` file only show up in the rendered report **after being pushed to the `develop` branch** on GitHub (the branch baked into the proxy URL) — there is no local preview step.

## Content conventions

- The report is written in **Spanish** (all chapters, tables, and commentary). Keep additions consistent with that unless asked otherwise.
- Chapters follow the SECR/DDD project template used across the course: Ch. I Introducción (startup/solution profile, Lean UX), Ch. II Requirements Elicitation & Analysis, Ch. III Requirements Specification (User Stories), Ch. IV Product Design (Style Guidelines, Bounded Contexts, C4/class diagrams), Ch. V Product Implementation, Validation & Deployment (Sprint Planning/Backlog, CI/CD, deployment evidence, conclusions).
- Git history on this repo follows GitFlow with PRs merged from feature/docs branches into `develop`, then into `main`/`release/*`. Commit messages follow Conventional Commits (`docs:`, `feat:`, `fix:`, `chore:`).
