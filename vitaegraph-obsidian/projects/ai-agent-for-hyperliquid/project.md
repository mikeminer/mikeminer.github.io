---
type: project
id: project:ai-agent-for-hyperliquid
title: AI Agent for Hyperliquid
related_records:
  - experience:autonomous-risk-systems-designer
  - experience:blockchain-testnet-validator
---

# AI Agent for Hyperliquid

## Executive summary

AI Agent for Hyperliquid is a public Solidity-oriented repository described as a 3-agent EVM trading system. The README uses the name OPENCLAW and describes AI analysis, on-chain execution, and automated exit-strategy concepts on HyperEVM.

Repository: https://github.com/mikeminer/ai-agent-for-hyperliquid  
Primary language: Solidity  
License: MIT  
Created: 2026-03-28  
Last pushed in public report: 2026-03-28

## Problem, users, and constraints

The project explores how AI-assisted analysis, trade-execution logic, and exit-strategy planning might connect to HyperEVM and Hyperliquid workflows. Because the domain involves trading and private keys, public positioning must emphasize safety boundaries, dry-run testing, explicit confirmation, and non-advisory status.

## Personal role and ownership

The available sources support Michele as repository owner and builder. The graph should not claim deployed contract usage, profitable trading, or security-audited smart contracts unless additional evidence is provided.

## Architecture and data flow

The README describes a three-stage flow:

- Agent 01 Brain: Monte Carlo-style analysis.
- Agent 02 Executor: long/short decision, Kelly fraction, leverage.
- Agent 03 Harvester: TP ladder and stop-loss.
- EVM Executor: smart-contract functions for signal execution and exit strategy.

The README also describes a project structure with contracts, orchestrator, frontend, docs, environment config, and Foundry tooling.

## Implementation details

Publicly described components include Solidity contract functions such as `executeSignal`, `setExitStrategy`, and `emergencyClose`, Python orchestrator pieces, a React/Vite frontend, and Foundry scripts/tests. These are README observations and should be confirmed directly before code-level claims.

## Technology choices

The project touches Solidity, Python, Node/React, Foundry, HyperEVM, wallet signing, and trading-agent orchestration.

## Outcomes, current state, and limitations

The public report observed MIT license and Solidity as primary language. The repository was created and last pushed on the same date, so current maturity should be treated cautiously.

## Repository observations

The AgentKit SEO GitHub fetcher completed without extraction warnings on 2026-07-07. It observed default branch `main`, non-fork, non-archived status, and MIT license.

## Career signals

This record supports Web3 Product Builder positioning through EVM architecture, smart-contract workflow thinking, agent orchestration, and Hyperliquid/HyperEVM experimentation.

## Public links

- GitHub: https://github.com/mikeminer/ai-agent-for-hyperliquid

## Open questions

- Are the contracts compiled and tested in CI?
- Was any contract deployed, or is this a local/dry-run prototype?
- Which parts are implemented beyond README description?
