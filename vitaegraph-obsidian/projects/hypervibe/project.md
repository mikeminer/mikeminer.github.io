---
type: project
id: project:hypervibe
title: HyperVibe
related_records:
  - experience:autonomous-risk-systems-designer
  - experience:blockchain-testnet-validator
---

# HyperVibe

## Executive summary

HyperVibe is a public JavaScript repository around Hyperliquid spot/perpetual workflows, wallet signing concepts, customizable tools, and a chat UI. The public README frames it as an AI-assisted trading agent that proposes trades and waits for approval before execution.

Repository: https://github.com/mikeminer/HyperVibe  
Primary language: JavaScript  
Topics observed: anthropic, anthropic-api, hyperliquid, hyperliquid-trading-bot, web3  
Created: 2026-03-28  
Last pushed in public report: 2026-04-12

## Problem, users, and constraints

The project targets local Hyperliquid trading workflow experimentation: market tooling, strategy playbooks, approval gates, monitoring, journaling, and AI model routing. Because this domain touches trading, public copy must include risk boundaries and avoid financial-performance claims.

## Personal role and ownership

The available source supports Michele as repository owner and builder. The project can be used as evidence of Web3/trading workflow prototyping, not as evidence of profitable autonomous trading.

## Architecture and data flow

The README describes a local app with a chat interface, market analysis tools, approval/rifiuta style permission gating, playbooks, skills, heartbeat monitoring, triggers, and learnings. It also describes a Tri-Hybrid engine routing prompts across local LLaMA/Ollama, OpenAI, and Anthropic Claude tiers based on a value score and escalation behavior.

## Meaningful implementation details

Publicly described primitives include market tooling, heartbeat, triggers, permissions, playbooks, and learnings. The README also describes a local bridge endpoint compatible with the Anthropic SDK and a local app that opens in the browser.

## Technology choices

The public report supports JavaScript as primary language and Hyperliquid/Web3-related topics. The README references local model routing, API bridges, chat UI, playbooks, and wallet signing concepts.

## Outcomes, current state, and limitations

The safe current-state claim is that HyperVibe is a public local trading workflow prototype. The README contains strong product language, but VitaeGraph should not convert that into claims of live autonomous trading success or financial return.

## Repository observations

The AgentKit SEO GitHub fetcher completed without extraction warnings on 2026-07-07. It observed no public license field, default branch `main`, and public topics related to Hyperliquid and Web3.

## Career signals

HyperVibe supports Web3 Product Builder positioning through wallet flows, chat-assisted operation, approval gates, model routing, and trading-tool UX. It also supports risk-systems positioning when framed around guardrails and explicit approval.

## Public links

- GitHub: https://github.com/mikeminer/HyperVibe

## Open questions

- Which safety mechanisms are implemented in source versus described in README?
- Are screenshots or a demo video available?
- Should the portfolio present this as a local prototype rather than a trading bot?
