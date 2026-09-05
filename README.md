<!--
  Nigmat Rahim — profile README
  Art direction: scientific instrument / terminal readout
  Every visual ships as a light/dark pair behind <picture>.
  Do not hardcode a background colour into any asset.
-->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/header-dark.svg">
  <img width="100%" alt="Nigmat Rahim — Biomedical AI · Agentic Research Systems · Bioinformatics" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/header-light.svg">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/panel-dark.svg">
  <img width="100%" alt="status readout" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/panel-light.svg">
</picture>

</div>

I build systems that take an ambiguous biomedical question and carry it through to a reproducible
analysis — literature, study design, data acquisition, execution, write-up. Medicine by training,
infrastructure by habit. Peking University, then Imperial College London — MSc Applied
Multiomics in Biomedicine, incoming 2026.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/divider-dark.svg">
  <img width="100%" alt="" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/divider-light.svg">
</picture>

## Selected work

| | Project | What it actually does | Stack |
|---|---|---|---|
| `01` | **[Bioagent](https://github.com/Nigmat-future/Bioagent)** | LangGraph multi-agent system running a full research loop — literature → hypothesis → data acquisition from GEO/NCBI/GDC/ENCODE → sandboxed analysis → write-up, with checkpointing and cost budgets | Python · LangGraph |
| `02` | **[ThyroPADA](https://github.com/Nigmat-future/thyroid-quiz)** | Thyroid-ultrasound case annotation platform: auth, multi-study support, CSV export. The largest codebase here | FastAPI · SQLAlchemy · Alembic |
| `03` | **[axon](https://github.com/Nigmat-future/axon)** | Local-first LLM router that auto-discovers provider keys on the machine and exposes one OpenAI/Anthropic-compatible localhost endpoint | Python |
| `04` | **[TopoLogos](https://github.com/Nigmat-future/TopoLogos)** | Spatial-transcriptomics reasoning partner with three Socratic personas — empiricist, dialectician, gadfly. Deliberately not a pipeline executor | Python · BioMCP |
| `05` | **[ci-coroner](https://github.com/Nigmat-future/ci-coroner)** | GitHub Action that autopsies failed CI runs and verifies every log line it cites actually exists before posting | TypeScript |
| `06` | **[skillgenesis](https://github.com/Nigmat-future/skillgenesis)** | Self-evolving skill system — agents write, refine and merge executable skills through adversarial self-play behind a regression gate | TypeScript |
| `07` | **[roast-my-pi](https://github.com/Nigmat-future/roast-my-pi)** | Parses publication and funding networks to compute a PI's independence ratio — whether they lead or ride team credit | HTML · JS |
| `08` | **[cellhop](https://github.com/Nigmat-future/cellhop)** | One-liner AnnData ↔ Seurat conversion in either direction, without dumping intermediate files | Python · R |

<details>
<summary><code>··</code>&nbsp; More — bioinformatics tooling, clinical apps, experiments</summary>

<br/>

| Project | |
|---|---|
| [biomedical-codex-skills](https://github.com/Nigmat-future/biomedical-codex-skills) | Nine-skill bundle for biomedical workflows — QC, pipeline triage, protocol-to-pipeline, RNA-seq scaffolding, HPC tuning |
| [rverflow](https://github.com/Nigmat-future/rverflow) | Resolves R package version conflicts across CRAN/Bioconductor/GitHub *before* install |
| [pad-to-vibe](https://github.com/Nigmat-future/pad-to-vibe) | Tablet sketches → local sync → MCP tool, so a coding agent can implement the drawing |
| [publishable-research-orchestrator](https://github.com/Nigmat-future/publishable-research-orchestrator) | Scores candidate research directions for publishability, then plans the winner |
| [Gastric-Cancer scRNA-seq Pipeline](https://github.com/Nigmat-future/Gastric-Cancer-scRNA-seq-Analysis-Pipeline---GSE163558) | Single-cell pipeline on GSE163558 |
| [pretext-med](https://github.com/Nigmat-future/pretext-med) | Streaming clinical report generation with zero layout shift |
| [scicolors](https://github.com/Nigmat-future/scicolors) | Scientific colour-palette toolkit |
| [MedInterprint](https://github.com/Nigmat-future/MedInterprint) · [diabeta-ai-insight](https://github.com/Nigmat-future/diabeta-ai-insight) · [AI-review-Literature](https://github.com/Nigmat-future/AI-review-Literature) | Clinical and literature web apps |

</details>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/divider-dark.svg">
  <img width="100%" alt="" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/divider-light.svg">
</picture>

## Readout

Measured across 35 non-fork public repositories — 6.71 MB of source.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/langbar-dark.svg">
  <img width="100%" alt="Language distribution: Python 50.4%, JavaScript 22.5%, TypeScript 15.7%, HTML 9.1%" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/langbar-light.svg">
</picture>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/output/github-snake-dark.svg">
  <img width="100%" alt="contribution graph" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/output/github-snake.svg">
</picture>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/divider-dark.svg">
  <img width="100%" alt="" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/divider-light.svg">
</picture>

## How I work

```
  modular            over    monolithic
  research-aware     over    generic
  execution-first    over    presentation-heavy
  real workflows     over    demo-only
```

<div align="center">

[**nigmat-future.github.io**](https://nigmat-future.github.io) &nbsp;·&nbsp; [**repositories**](https://github.com/Nigmat-future?tab=repositories)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/footer-dark.svg">
  <img width="100%" alt="" src="https://raw.githubusercontent.com/Nigmat-future/Nigmat-future/main/assets/footer-light.svg">
</picture>

</div>
