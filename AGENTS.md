# Open Wiki Agent Guide

## Purpose

Maintain public, source-backed Markdown wikis compiled from public internet knowledge.

This repository is optimized for humans and AI agents: plain files, stable links, explicit provenance, and useful synthesis over transcript dumping.

## Global Rules

- Do not publish full copyrighted transcripts by default.
- Preserve links to original sources.
- Prefer timestamped citations and short excerpts over wholesale reproduction.
- Every wiki page should start with a one-paragraph summary.
- Use `[[wikilinks]]` between related pages.
- Keep channel/source-specific wikis under `wikis/<source>/`.
- Put cross-source synthesis in `synthesis/` only after patterns appear in multiple source wikis.
- Update the relevant `INDEX.md` and `log.md` whenever sources are ingested or wiki pages change.
- If a source is unavailable, members-only, transcript-disabled, or otherwise inaccessible, record that in the manifest instead of pretending it was processed.

## Layer Model

1. **Manifest**: list of candidate sources and ingestion status.
2. **Episode/source notes**: concise source-backed notes with metadata, timestamps, key ideas, and links. No full transcript dumps.
3. **Wiki pages**: durable topic pages maintained over time.
4. **Synthesis pages**: cross-corpus patterns and implementation ideas.

## Build-First Rule

Prioritize making the wiki thick and useful before creating promotional artifacts. Do not add public post drafts, weekly content drafts, or marketing wrappers to the repo unless explicitly requested. Shareable value should come from strong wiki pages and synthesis, not thin outputs.
