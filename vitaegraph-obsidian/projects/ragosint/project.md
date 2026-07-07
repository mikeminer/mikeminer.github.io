---
type: project
id: project:ragosint
title: RAGOSINT
related_records:
  - experience:artificial-intelligence-researcher
  - experience:isipm-project-manager
---

# RAGOSINT

## Executive summary

RAGOSINT is a TypeScript public-source intelligence and RAG-oriented system for turning public Italian sources into operational intelligence. The public repository describes collection, knowledge-base organization, indexing, periodic updates, alerts, RSS feeds, reports, semantic search, and an exportable Obsidian brain.

Repository: https://github.com/mikeminer/RAGOSINT  
Live MVP reported in README: https://ragosint.vercel.app/  
Primary language: TypeScript  
License: MIT  
Created: 2026-06-18  
Last pushed in public report: 2026-07-02

## Problem, users, and constraints

The project targets builders or teams that need to monitor public sources such as Italian regulations, public tenders, procurement signals, PNRR-related material, privacy, AI, cybersecurity, digital public administration, accessibility, DORA, MiCA, and related compliance/opportunity areas. The README positions it as more than a scraper: a pipeline that normalizes sources, extracts operational signals, and exposes consultable outputs.

The system is constrained by public-source freshness, serverless runtime behavior, cache windows, and source availability. The README states that the project currently does not use a persistent database for RSS generation; feeds are generated through the serverless pipeline and cached.

## Personal role and ownership

The available sources support Michele as the public repository owner and project builder. Do not infer adoption, customer usage, production reliability, or institutional endorsement from repository presence alone.

## Architecture and data flow

The public README describes a flow from configured public sources into normalized alerts and outputs. RSS clients request feeds, Vercel runs source collection, alerts are normalized, RSS XML is produced, and responses are cached. A daily Vercel cron endpoint warms or verifies channels.

The README also describes an exportable Obsidian brain with Markdown notes, YAML frontmatter, internal links, graph navigation, tags, channels, and ZIP exports for full, normative, or tender-specific brains.

## Implementation details

Observed public features include:

- RSS channels for normativa, bandi, and aggregate feed.
- Semantic search endpoint examples.
- Obsidian brain export endpoints.
- Alert/report/search/vector-store style API concepts.
- Normative monitoring categories including AI Act, NIS2, GDPR, PA digitalization, accessibility, DORA, MiCA, and AML-related signals.

## Technology choices

TypeScript is the primary public repository language. The public README mentions Vercel, RSS, semantic APIs, vector-store concepts, and Obsidian export. Treat deeper implementation details as needing direct source inspection before making stronger claims.

## Outcomes, current state, and limitations

The repository report observed an MIT license, a non-fork, non-archived repository, and a public README with live MVP links. The README itself is detailed, but the actual runtime state of the live service should be checked before saying it is currently operational.

## Repository observations

The AgentKit SEO GitHub fetcher completed without extraction warnings on 2026-07-07. It observed no topics, TypeScript as primary language, default branch `main`, and MIT license.

## Career signals

RAGOSINT is strong evidence for AI Automation Engineer positioning: RAG, OSINT, public-source monitoring, operational intelligence, reporting, RSS feeds, semantic search, and Obsidian graph export. It is also relevant to public-sector opportunity monitoring and compliance-aware product thinking.

## Public links

- GitHub: https://github.com/mikeminer/RAGOSINT
- Live MVP from README: https://ragosint.vercel.app/

## Open questions

- Which pipeline components are implemented versus planned?
- Are there screenshots or architecture diagrams that should be linked in the portfolio?
- Should RAGOSINT become a featured case study for the AI Automation Engineer direction?
