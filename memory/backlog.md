# Starting backlog — day one

- First audit: engine_test coverage vs README gaps (output/tool HTTP paths lack dedicated unit tests; OutputVerdict CEL fields incomplete).
- SHARED backlog with agent-gate: redteam/scripts/audit_reserved_adapt_defense_in_depth.py — maps Adapt bypasses to default.yaml tool_rules (IRREVERSIBLE escalate only; MEDIUM/HIGH default allow). Produce a real finding: which rules should tighten for enforcer sell.
- Tenant overrides sprawl: dozens of e2e/qa tenant override YAMLs under policies/tenants/ — audit which are fixtures vs live risk.
