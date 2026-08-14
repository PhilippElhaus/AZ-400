# Repository agent instructions

## Working standard

- Write English documentation and agent text in ASD-STE100-oriented technical
  English. Use active voice, short sentences, one instruction per step, and
  consistent terms. Keep exact source text unchanged.
- Use trunk-based development. `main` is the only long-lived branch. Start
  from updated `main`. Keep feature branches small and short-lived.
- Merge validated branches into `main` as soon as authority permits. Delete
  merged branches, prune refs, and never force-push `main`.
- If work cannot merge, record its branch, commit, checks, remaining work, and
  owner. This policy does not authorize Git or live mutations.
- Prefer Rust over Python for new components and substantial rework when Rust
  is practical. Prioritize it for long-running, privileged, concurrent,
  network-facing, performance-sensitive, or system-level code.
- Keep the established language when it is safer or its ecosystem requires it.
  Do not rewrite only to change language. Preserve interfaces, schemas,
  deployment, rollback, and resource limits.

## Credential and LAN safety

- Change credentials only with Philipp's exact authorization. Exposure and
  broader tasks do not give this authority. Report exposure without its value.
- Keep secrets, keys, certificates, customer data, and runtime exports out of
  Git, output, logs, documentation, fixtures, and process arguments.
- For authorized LAN work, follow `D:\AGENTS.md`. Never open or expose
  `D:\.env`. Materialize one exact item to a new ACL-restricted temporary
  path. Remove it immediately.
- Do not guess item names or recreate `.local-secrets/`.
