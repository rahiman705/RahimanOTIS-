# DT Infrastructure Task Agent

Source package for implementing the DT Infrastructure Task Agent in Microsoft Copilot Studio.

## Purpose
Help infrastructure teams analyze requests, classify work, identify missing information, use approved knowledge, and recommend safe next actions.

## Topics
- Infrastructure Request Triage
- Infrastructure Incident
- Installation Request
- Infrastructure Upgrade
- Change Request
- Vendor Coordination
- Site Readiness
- Find Infrastructure Documentation

## Repository structure
- `instructions/` agent-level instructions
- `topics/` topic definitions and trigger phrases
- `entities/` controlled classification entities
- `variables/` shared and topic-specific variables
- `tests/` acceptance scenarios
- `docs/` architecture and implementation notes

## Safety principle
The agent may assist with analysis and planning, but high-impact production, security, access, firewall, disruptive service, or deletion actions require appropriate human authorization.
