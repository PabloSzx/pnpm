---
"@pnpm/config": minor
"@pnpm/plugin-commands-installation": minor
"@pnpm/plugin-commands-rebuild": minor
"@pnpm/plugin-commands-script-runners": minor
---

Add `workspace-concurrency` based on CPU cores amount, just set `workspace-concurrency` as zero or negative, the concurrency limit is set as `max((amount of cores) - abs(workspace-concurrency), 1)`
