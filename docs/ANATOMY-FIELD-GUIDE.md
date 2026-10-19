# Anatomy field guide · ABGN

These figures are **interfaces to ideas**, not production monitoring. This page is the reading key: what the reader is seeing, what each mechanical part means, which numbers belong to real portfolio records, and how to inspect the underlying work.

## Figure 01 · The Evidence Press

An original SVG/JavaScript illustrative model of an AI-assisted engineering workflow. You can select each of six stations in the [interactive HTML file](../demos/evidence-press.html) (download it and open in a browser).

| Physical mechanism | Engineering interpretation | What is actually demonstrated |
|---|---|---|
| Input feeder | Bounded intent or change request | Simulated intake state |
| Knowledge wheels | Reusable conventions and project-specific KB Dev / KB Doc context | Illustrative context transfer, no live retrieval |
| Specification press | SDD contract and acceptance criteria | Simulated workpiece constraint |
| Agent carriage | Scoped candidate implementation | Illustrative movement, no generated real PR |
| Three independent gates | Definition of Ready, Definition of Done, adversarial review | Simulated reject/pass state machine |
| Evidence tray | Accepted output plus reproducible evidence | Illustrative exit, not a production deployment |

**Interaction contract.** Select a stage, inspect its explanation, use next/previous to move a single workpiece, simulate a failed review, or reset. The text, animation and gate readout use the same six-state model; none of the outputs proves any client deployment.

**See related public work:** [A2A Agentic Platform](https://github.com/jandromani/A2A) and [portfolio case studies](https://alejandrobgn.vercel.app/experience). Project architectures should be assessed on their own documented evidence.

## Figure 02 · Career Gauge

The measuring instrument encodes seven professional chapters from GIS to AI engineering. The blocks are career chapters; block height represents the months attributed to that role in the original dated figure. The carriage and dial refer to the selected chapter; the pointer is not a skills or compensation score.

| Chapter | Period shown in career source | Scope |
|---|---|---|
| Esri España | 2015 | GIS infrastructure and services |
| Repsol / Accenture | 2015–2017 | GIS tools and workflow automation |
| Grupo AVALON | 2017–2019 | Java and public-sector application modernisation |
| Hewlett Packard Enterprise | 2019–2022 | Enterprise and telecom backend systems |
| NTT DATA | 2022–2024 | Technical leadership and distributed platforms |
| Ayesa | 2024–2026 | Technical leadership and AI enablement |
| knowmad mood | 2026– | Tech Lead AI and agentic engineering |

**Evidence boundary.** The original gauge is based on a historical career snapshot. The visual timing is illustrative and does not update the months of the current role in real time. Check the [Experience page](https://alejandrobgn.vercel.app/experience) for the full narrative and dated details. Do not infer headcount, ROI, seniority or salary from the height of a block.

## Figure 03 · Evolution Catalog

A real-looking filing cabinet with four drawers; each drawer represents one calendar year of a dated personal R&D archive. Each individual card represents a recorded research artefact, **not a commercial product, released service or independent deployment**.

| Year | Recorded artefacts in the July 2026 snapshot | Share of 184 |
|---|---:|---:|
| 2023 | 14 | 7.6% |
| 2024 | 15 | 8.2% |
| 2025 | 39 | 21.2% |
| 2026, through July | 116 | 63.0% |
| **Total** | **184** | **100%** |

The archive's original provenance categories distinguish **133 confirmed** records from **51 reconstructed from memory**. Those are archive labels, not external audit opinions. The rapid 2026 increase is an artefact-count distribution, not evidence of 116 shipped applications.

**What to inspect:** [Evolution timeline](https://alejandrobgn.vercel.app/evolution). The current GitHub illustration is a preserved snapshot; it must not be silently refreshed with invented counts.

## Source, rendering and status

- SVG visuals: [Evidence Press](../assets/evidence-press-dark.svg), [Career Gauge](../assets/career-gauge-dark.svg), [Evolution Catalog](../assets/evolution-catalog-dark.svg).
- GitHub-safe variants of the last two replace inherited CSS variables with explicit vector styles. They are presentation variants of the user's original SVG figures; the original sources remain available in `assets/`.
- An SVG or static preview on GitHub cannot run the full interactive inspector. For the live local interaction, download the self-contained HTML from `demos/` and open it in a browser.
- Evidence Press is an original ABGN object study inspired by [Anatomy](https://skills.wheresryan.sh/anatomy); it is **not** the output of the official Anatomy skill.

## Future rule for new objects

Every new object needs the same four pieces of metadata: **a named physical mechanism**, **its mapping to an actual engineering problem**, **an inspectable state/interaction**, and **an evidence limit**. Numbers shown on an object must come from a named, versioned data source or be explicitly labelled simulated.
