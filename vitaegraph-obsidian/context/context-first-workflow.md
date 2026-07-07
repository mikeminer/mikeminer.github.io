# AgentKit SEO Context-First Workflow

## Principle

The first base workflow should be `agentkit-seo-agent-context-optimization`: create or maintain the personal career context file before asking any platform skill or VitaeGraph to produce output.

The compact context file answers:

- What facts are verified?
- What goals and target roles are stated intent?
- Which public claims are safe?
- Which claims need evidence?
- Which facts should not be invented, upgraded, or repeated?

VitaeGraph answers a different need: when there is enough material, it expands that compact source of truth into detailed linked records for roles, projects, education, certifications, awards, publications, and their relationships.

## Current context file

Private source-of-truth path:

```text
~/.agentkit-seo/michele-angelo-forlani-career-context.md
```

This public vault does not copy the full private context file. It uses a public-safe subset already represented in the portfolio, CV pages, LinkedIn-derived professional facts, and public GitHub repository reports.

## Recommended operating sequence

1. Create or update the personal career context file with `agentkit-seo-agent-context-optimization`.
2. Validate the context file: chronology, roles, projects, education, skills, evidence boundaries, goals, and claims to avoid.
3. If the task is narrow, hand off to one platform skill: CV/ATS, GitHub, LinkedIn, web portfolio, or X/Twitter.
4. If the material is broad enough, build or update VitaeGraph with `agentkit-seo-vitaegraph`.
5. Use VitaeGraph for deep retrieval, Obsidian navigation, project case studies, role evidence, and cross-record relationships.

## Why this matters

Starting with the context file reduces drift. It prevents a graph, CV, LinkedIn rewrite, or portfolio page from becoming a second source of truth with unsupported claims. The graph should deepen and connect facts; it should not invent facts to fill empty nodes.

## Public-output guardrails

- Keep verified history separate from target direction.
- Keep goals and growth areas as stated intent.
- Do not turn "interested in" into "experienced in" unless the project or role record proves it.
- Do not publish private credential IDs, private hotel data, private analytics, phone numbers, addresses, or API keys.
- Use "prototype", "concept", "research", "experiment", or "public repository" when production maturity is not proven.
