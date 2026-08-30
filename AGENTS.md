# Repository agent guide

## Scope and precedence

Read [README.md](README.md) before changing this repository. Apply the
closest nested `AGENTS.md` when one exists. Work coordinated from `D:\`
also follows `D:\AGENTS.md`.

## Working standard

- Use ASD-STE100-oriented technical English. Keep code, commands, paths,
  identifiers, quotations, and logs exact.
- Use updated `main` as the only long-lived branch. Keep feature branches
  small. Delete merged branches and prune refs.
- Never force-push `main`. Record the commit, validation, remaining work,
  and owner when work cannot merge.
- Git policy does not authorize a commit, push, pull request, workflow,
  release, deployment, or live mutation.
- Prefer Rust for new system-level components when practical. Keep the
  established language when it is safer. Preserve stable interfaces and
  rollback paths.

## Delivery and safety

- For a bug or issue fix, implement and validate it. Then commit, push, and
  deploy through the documented path unless the user excludes a step.
- Preserve unrelated tracked and untracked work. Never reset, clean, stash,
  or overwrite it.
- Change a credential only with Philipp's exact authorization. Report
  exposure without repeating the value.
- Keep secrets, keys, certificates, customer data, and runtime exports out of
  Git, output, logs, docs, fixtures, and process arguments.
- Source work does not authorize other live or external actions.
- For authorized LAN work, follow `D:\AGENTS.md`. Never open or expose
  `D:\.env`. Materialize one exact item to a new restricted temporary path,
  then remove it.
- Never guess secret item names or recreate `.local-secrets/`.

## Validation

Run the narrow checks documented in the README. Finish with
`git diff --check` and `git status --short`. Report unavailable checks and
remaining work.
