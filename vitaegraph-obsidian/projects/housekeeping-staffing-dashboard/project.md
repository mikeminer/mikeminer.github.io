---
type: project
id: project:housekeeping-staffing-dashboard
title: Housekeeping Staffing Dashboard
related_records:
  - experience:night-auditor-roberto-naldi-collection
  - experience:artificial-intelligence-researcher
  - project:python-launcher-pro
  - education:executive-master-hotel-management-tourism-4-0
---

# Housekeeping Staffing Dashboard

## Executive summary

Housekeeping Staffing Dashboard is a Python/Tkinter Windows-oriented project for estimating daily housekeeping staffing needs from hotel workload data. The public README frames it as decision support for housekeeping staffing, cost control, and operational planning.

Repository: https://github.com/mikeminer/Housekeeping-Staffing-Dashboard-Python-  
Primary language: Python  
Created: 2026-01-29  
Last pushed in public report: 2026-05-20

## Problem, users, and constraints

The project addresses a concrete hotel management problem: housekeeping staffing is costly and difficult to size from subjective estimates. The tool translates occupancy and PMS XML data into estimated work minutes and recommended staff levels.

Target users described in the README include directors, operations managers, housekeeping managers, and hotel structures from 3-star to 5-star contexts.

## Personal role and ownership

The project aligns strongly with Michele's night-audit and hospitality-operations background. Available sources support him as repository owner and project builder. Claims about operational deployment inside a specific hotel should remain cautious unless explicit approval or evidence is added.

## Architecture and data flow

The README describes a flow from PMS XML data into workload calculations based on stayover rooms, departures, and arrivals. Each activity is translated into work minutes, summed, and compared with available work time per staff member. The output is a daily table with date, occupancy level, estimated workload, and recommended number of housekeeping staff.

## Implementation details

Publicly described capabilities include configurable parameters, persistent settings, automatic saving, popup explanations, and non-technical usability. The README recommends launching it through Python Launcher PRO to reduce setup friction.

## Technology choices

Python and Tkinter support a Windows desktop utility pattern. This choice fits hotel operational settings where a lightweight local tool can be easier than a cloud platform.

## Outcomes, current state, and limitations

The repository report observed no public license field and no topics. The strongest safe claim is that the project demonstrates practical hospitality automation and decision-support design. Production usage or quantified savings need evidence.

## Repository observations

The AgentKit SEO GitHub fetcher completed without extraction warnings on 2026-07-07. It observed primary language Python, default branch `main`, and a non-archived public repository.

## Career signals

This is one of the strongest records for Hospitality Tech / Operations Automation because it bridges direct hotel domain knowledge, PMS data, non-technical UX, staffing decisions, and Python implementation.

## Public links

- GitHub: https://github.com/mikeminer/Housekeeping-Staffing-Dashboard-Python-

## Open questions

- What PMS XML fields are parsed?
- Are there anonymized sample files that can be safely included?
- Has the tool been used in real planning sessions, and can that be stated publicly?
