# LLM Persona, Personalization, and Consciousness-Adjacent Papers

Curated papers and research map for building, evaluating, and critiquing persona-driven and personalized LLM agents.

![version](https://img.shields.io/badge/version-2026.05-lightgrey)
![license](https://img.shields.io/badge/license-CC--BY--4.0-green)
![docs](https://img.shields.io/badge/docs-available-blue)
![repo](https://img.shields.io/badge/repo-research%20map-blue)

[Install](#install) • [Quick Start](#quick-start) • [Features](#features) • [Architecture](#architecture) • [Security](#security) • [Roadmap](#roadmap) • [Contributing](#contributing) • [License](#license)

This repository is a curated paper bundle for researchers, builders, and reviewers working on LLM persona, personalization, long-term memory, self-modeling, introspection, and related evaluation questions. It is designed for people who need a compact starting point for literature review, benchmark discovery, and research framing rather than a general-purpose dump of loosely related papers.

The collection prioritizes representative and recent work from 2025-2026, with selected 2024 papers retained for benchmark, taxonomy, or method value. Consciousness-related material is included with a narrow scope: this repo tracks consciousness-adjacent functional components and evaluation signals, not claims that current LLMs are conscious.

## Install

No software installation is required to use this repository as a reading pack.

```bash
git clone https://github.com/<your-github-username>/llm-persona-personalization-papers.git
cd llm-persona-personalization-papers
```

Optional local setup:

- Use any PDF reader for the paper files.
- Use a spreadsheet tool or script-friendly workflow to inspect `manifest.csv`.
- Optional: run your own metadata validation or link checks against the manifest files.

## Quick Start

1. Use [`manifest.csv`](./manifest.csv) or [`00_Index_and_notes/manifest.csv`](./00_Index_and_notes/manifest.csv) to locate papers, sources, page counts, and notes.
2. Read the surveys in [`01_Surveys_Frameworks/`](./01_Surveys_Frameworks/) first, then move through persona, personalization, memory, introspection, and evaluation.
3. Review [`00_Index_and_notes/taxonomy_CN.md`](./00_Index_and_notes/taxonomy_CN.md) for the eight-topic research framing.
4. Check [`00_Index_and_notes/link_only_and_watchlist.md`](./00_Index_and_notes/link_only_and_watchlist.md) for important papers not bundled as local PDFs.

## Features

- Curated scope instead of broad scraping: the repo focuses on persona, personalization, self-continuity, self-modeling, and evaluation-relevant adjacent topics.
- Recent-paper bias with explicit retention logic: 2025-2026 is primary, while older work is included only when it still carries benchmark or framing value.
- Structured reading flow: the papers are grouped into eight folders that map cleanly onto a review or survey outline.
- Manifest-backed navigation: metadata includes title, year, source, URL, local path, page count, and short notes.
- Boundary-aware consciousness coverage: theory and introspection papers are included as functional or evaluative signals, not as proof of subjective consciousness.
- Watchlist support: the repo tracks high-value papers that were not bundled locally because of access limits, freshness, or curation status.



## Security

This repo is low-risk from a software-execution perspective because it currently contains documents and metadata rather than runnable application code, but it still has important integrity and usage constraints.

- Source provenance matters: every bundled paper should keep a verifiable public source URL in the manifest.
- Copyright boundaries matter: only include papers that are publicly accessible from legitimate sources; do not bypass paywalls or upload restricted copies.
- Claim discipline matters: consciousness-related papers should be described as consciousness-adjacent, introspective, or self-modeling evidence where appropriate, not as proof that an LLM is conscious.
- Metadata integrity matters: titles, years, venues, URLs, and file paths should be updated carefully to avoid citation drift.
- PDF provenance matters: replacements should preserve source traceability and should not swap in files from unverifiable mirrors.


## Contributing

Contributions are welcome if they improve the quality of the collection without expanding it into an uncurated archive.

- Open an issue or PR for metadata fixes, broken links, missing source URLs, or better categorization.
- When proposing a new paper, explain why it belongs in the current scope and which folder it should live in.
- Prefer adding notes to the manifest or watchlist when a paper is relevant but not suitable for local bundling.
- Do not submit files that are paywalled, licensing-restricted, or unverifiable in origin.
- Keep filename conventions and manifest fields consistent with the existing repository structure.

## License

This repository now includes a root [`LICENSE`](./LICENSE) for original curation materials in the repo.

- Repository metadata and original documentation are licensed under `CC BY 4.0`.
- Bundled paper rights remain with their respective authors, publishers, or hosting venues.
- Third-party PDFs are not relicensed by this repository; redistribute them only when the original source permits it.
