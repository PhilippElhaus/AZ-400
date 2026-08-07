# Repository agent instructions

## Credential safety

- Never create, change, rotate, reset, revoke, or delete any credential or
  authentication setting unless Philipp explicitly instructs that exact
  change.
- Suspected or actual exposure does not grant permission to rotate a
  credential. Stop, report the issue, and ask for explicit authorization.
- Do not infer credential-change authorization from a broader debugging,
  deployment, security, recovery, or repair request.

## LAN and Vaultwarden secret discovery

- For an explicitly authorized LAN login or privileged operation, start with
  `D:\AGENTS.md`. The ACL-restricted `D:\.env` is only the Windows Vaultwarden
  bootstrap; it is not a repository env file and does not hold the target
  machine's operational secret.
- Never open, print, source, copy, or commit `D:\.env` directly. Use
  `D:\Vaultwarden\scripts\vaultwarden-local.ps1` as documented by the root
  guide to locate the appropriate shared `Elhaus` collection and materialize
  only the exact authorized file-backed item to a new ACL-restricted temporary
  path outside the repository. Remove that file immediately after use.
- LAN logins, sudo credentials, SSH/private keys, certificates, and recovery
  material belong in the relevant host/service collection. Do not guess item
  names, recreate `.local-secrets/`, or rotate credentials by inference.
