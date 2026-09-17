# Audit log

## 2026-09-17T16:46Z — hire-day seed audit

- Inventory: 85 files (many tenant override YAMLs), 13 Go, **4** tests.
- README gaps: output/tool HTTP paths lack dedicated unit tests; `judge_votes` / `escalation_reason` not in CEL; gRPC HTTP-only.
- **SHARED inherit:** `redteam/scripts/audit_reserved_adapt_defense_in_depth.py` — maps Adapt bypasses to `policies/default.yaml` tool_rules (only IRREVERSIBLE → escalate; MEDIUM/HIGH → default allow). Co-own with agent-gate; produce tightening proposal as PR to default.yaml / catalog — do not lose this backlog (redteam agent not hired in Phase 1).
- Tenant override sprawl under `policies/tenants/` needs fixture-vs-live classification.
