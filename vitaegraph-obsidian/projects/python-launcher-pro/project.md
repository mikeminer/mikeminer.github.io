---
type: project
id: project:python-launcher-pro
title: Python Launcher PRO
related_records:
  - project:housekeeping-staffing-dashboard
  - experience:artificial-intelligence-researcher
  - experience:night-auditor-roberto-naldi-collection
---

# Python Launcher PRO

## Executive summary

Python Launcher PRO is a Windows batch-based launcher designed to make Python scripts easier to run for non-technical users. It supports guided script selection, dependency installation, Python version selection, Python 3.11 installation through winget, and AST-based dependency auto-detection.

Repository: https://github.com/mikeminer/Python-Launcher-PRO  
Primary language: Batchfile  
Created: 2026-01-28  
Last pushed in public report: 2026-02-04

## Problem, users, and constraints

Many operational Python tools fail at the setup layer: missing Python versions, missing dependencies, unclear launch commands, or no `requirements.txt`. This project reduces that friction for Windows users and non-technical operators.

## Personal role and ownership

The public repository supports Michele as owner and builder. The tool is described as universal support for trading, data analysis, automation, business tools, and internal software.

## Architecture and data flow

The README describes a `.bat` launcher with a main menu and settings menu. The key dependency auto-detect flow analyzes Python files, uses Python's AST parser to identify imports, filters standard-library and built-in modules, generates `requirements_auto.txt`, and installs detected dependencies.

## Implementation details

Publicly described features include:

- Automatic `.py` discovery.
- Guided script launch.
- Base and optional library installation menus.
- Manual requirements install.
- Auto-detect dependencies.
- Python 3.11 installation with winget.
- Default Python version storage.

## Technology choices

Batchfile is appropriate for the Windows setup layer because the tool exists before the target Python environment is necessarily configured. The use of Python AST for dependency detection is a meaningful implementation decision because it avoids fragile regex-based import parsing.

## Outcomes, current state, and limitations

The public report did not observe a license field. The README states "Uso libero", but stronger licensing statements should be checked before reuse. The safe claim is that it is a setup and launch utility for Python-based operational tools.

## Repository observations

The AgentKit SEO GitHub fetcher completed without extraction warnings on 2026-07-07. It observed no public description, no topics, primary language Batchfile, default branch `main`, and a non-archived public repository.

## Career signals

Python Launcher PRO supports AI Automation Engineer and Hospitality Tech positioning by showing attention to deployment friction, non-technical users, Windows environments, dependency management, and operational usability.

## Public links

- GitHub: https://github.com/mikeminer/Python-Launcher-PRO

## Open questions

- Should the repository add an explicit license?
- Are there screenshots or installation demos that can strengthen portfolio trust?
