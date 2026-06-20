# Koerner Office Wiki Agent Guide

## Corpus

This wiki compiles useful business ideas, implementation tactics, and recurring patterns from public videos by Chris Koerner / The Koerner Office Podcast.

## Scope

Initial scope: public YouTube videos from 2026-01-01 onward.

## What to extract

For each video, capture:

- title, URL, video ID, upload date, duration
- short source summary
- concrete business ideas
- customer segments mentioned
- pricing / revenue clues
- acquisition channels
- operational steps
- tools or AI workflows
- notable caveats or claims to verify
- timestamped citations for important claims
- related wiki pages to update

## What not to publish

- Do not publish full transcripts by default.
- Do not quote long passages.
- Use short excerpts only when needed for context.
- Always link back to the original video.

## Wiki page rules

- Topic pages live in `wiki/`.
- Each page starts with a one-paragraph summary.
- Use lowercase kebab-case filenames.
- Use `[[wikilinks]]` to connect related ideas.
- Add source references under a `## Sources` heading.
- Update `INDEX.md` when creating or meaningfully changing pages.
- Append a log entry to `log.md` after each ingest batch.

## Page creation thresholds

Create or update a wiki page when a topic is:

- central to one video, or
- repeated across multiple videos, or
- directly useful as a weekly public artifact.

## First recommended topic pages

- `ai-enabled-service-businesses.md`
- `boring-business-ideas.md`
- `local-service-lead-generation.md`
- `government-and-public-sector-opportunities.md`
- `tiny-tools-and-micro-apps.md`
- `one-person-businesses.md`
- `sales-and-distribution-playbooks.md`
