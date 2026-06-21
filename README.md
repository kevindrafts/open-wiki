# Open Wiki

Open Wiki is a Markdown-first project for turning useful public internet knowledge into durable, interlinked wikis.

The first corpus is **Koerner Office**: practical business ideas, AI-enabled services, side hustles, boring businesses, distribution patterns, and implementation playbooks extracted from public YouTube videos.

## Start here

- [Koerner Office Wiki Index](wikis/koerner-office/INDEX.md)
- [AI-Enabled Service Businesses](wikis/koerner-office/wiki/ai-enabled-service-businesses.md)
- [Food and Beverage Concessions](wikis/koerner-office/wiki/food-and-beverage-concessions.md)
- [Raw Land Wholesaling](wikis/koerner-office/wiki/raw-land-wholesaling.md)

## What this is

A source-backed wiki of practical ideas hiding inside long videos, podcasts, interviews, and essays.

Most useful internet knowledge is trapped in hour-long episodes. Search and transcripts help, but they do not compound. This repo uses the Karpathy-style LLM wiki pattern: sources are processed into stable wiki pages that improve over time.

The goal is not to summarize everything. The goal is to compile reusable patterns:

- business ideas
- operating playbooks
- pricing clues
- customer segments
- acquisition channels
- implementation steps
- caveats and claims to verify
- links back to original sources

## What this is not

- Not a full transcript archive
- Not a replacement for the original creators' work
- Not legal, financial, or business advice
- Not a claim that every source is correct
- Not a content-marketing wrapper around thin notes

The repo should link back to original sources, use short timestamped citations, and avoid publishing full copyrighted transcripts by default.

## Current corpus

### Koerner Office

- Channel: [Chris Koerner on The Koerner Office Podcast](https://www.youtube.com/@thekoerneroffice)
- Initial scope: public videos from 2026-01-01 onward
- Discovery status: 72 public 2026 videos found, plus 1 skipped members-only item in the first 120 channel entries
- Ingest status: 37 ingested, 35 in backlog; see [`wikis/koerner-office/manifest.csv`](wikis/koerner-office/manifest.csv)

## Repo structure

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
scripts/               # helper scripts later
```

## Build order

This repo should become useful before it becomes promotional.

1. Ingest enough sources to make the wiki meaningfully browsable.
2. Thicken topic pages with repeated patterns across multiple episodes.
3. Add cross-source synthesis only after the source-specific wiki has enough density.
4. Publish/share only when the wiki feels like a useful artifact on its own.

## Contributing / source requests

Open an issue with a public source suggestion. Good suggestions include a YouTube channel, playlist, podcast, article archive, or a specific video that contains practical business, startup, dev, or implementation knowledge.

## Guiding idea

The future of saved content is not bookmarking. It is compilation.

Raw sources are the dirt. Wiki pages are the crops.
