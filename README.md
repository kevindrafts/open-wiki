# Open Wiki

Open Wiki is a public, Markdown-first knowledge base for compiling useful public internet knowledge into durable, interlinked wikis.

The first corpus is **Koerner Office**: practical business ideas, AI-enabled services, side hustles, boring businesses, distribution patterns, and implementation playbooks extracted from public YouTube videos.

## Why this exists

Most useful YouTube/podcast knowledge is trapped in long episodes. Search and transcripts help, but they do not compound. This repo uses the Karpathy-style LLM wiki pattern: sources are processed into stable wiki pages that improve over time.

The goal is not to redistribute transcripts. The goal is to create source-backed synthesis: reusable ideas, patterns, playbooks, questions, and links back to the original public videos.

## Structure

```txt
wikis/
  koerner-office/
    AGENTS.md          # local operating rules for this corpus
    INDEX.md           # wiki index and source coverage
    manifest.csv       # videos discovered for ingestion
    episodes/          # one source note per video, no full transcript dumps
    wiki/              # durable topic pages
    log.md             # chronological ingest/query/lint log
synthesis/             # cross-channel synthesis pages later
scripts/               # helper scripts
```

## First corpus

- Channel: [Chris Koerner on The Koerner Office Podcast](https://www.youtube.com/@thekoerneroffice)
- Initial scope: public videos from 2026-01-01 onward
- Current discovery: 72 public 2026 videos found, plus 1 skipped members-only item in the first 120 channel entries

## Publishing loop

Each weekly pass should produce:

1. new or updated episode notes
2. updated wiki pages
3. one public artifact worth sharing
4. a short post draft linking to the artifact

