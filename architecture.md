# Architecture

## Logical flow

User request
  -> Request Triage
  -> Specialist topic
  -> Approved knowledge lookup
  -> Facts + missing information + risks
  -> Recommended next action
  -> Human review for high-impact actions

## Specialist topics
- Incident
- Installation
- Upgrade
- Change
- Vendor Coordination
- Site Readiness
- Documentation Search

## Implementation principle
Keep stable classification values as entities. Keep changing operational data such as site names, device names, addresses, owners and vendor contacts in authoritative organizational data sources where practical rather than maintaining large static synonym lists.
