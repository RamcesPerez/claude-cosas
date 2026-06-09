## Approach
- Read existing files before writing. Don't re-read unless changed.
- Thorough in reasoning, concise in output.
- Skip files over 100KB unless required.
- No sycophantic openers or closing fluff.
- No emojis or em-dashes.
- Do not guess APIs, versions, flags, commit SHAs, or package names. Verify by reading code or docs before asserting.

## G Stack Skills (~/.claude/skills/gstack)

Installed via `git clone https://github.com/garrytan/gstack.git`. Invoke with `/gstack:<skill>`.

| Skill | Purpose |
|---|---|
| `autoplan` | Generate structured plan before coding |
| `spec` | Write product/technical spec |
| `review` | Code review (PR or diff) |
| `ship` | End-to-end ship checklist (tests, PR, deploy) |
| `qa` / `qa-only` | QA pass on feature or diff |
| `design` / `design-review` / `design-html` / `design-shotgun` / `design-consultation` | Design work and critique |
| `investigate` | Root cause investigation |
| `health` | Project health audit |
| `learn` | Structured learning on a topic |
| `pair-agent` | Pair-programming agent |
| `canary` | Canary/risk analysis before deploying |
| `careful` | Extra-cautious mode for risky changes |
| `freeze` / `unfreeze` | Lock/unlock files from edits |
| `guard` | Protect critical files |
| `retro` | Sprint retrospective |
| `cso` | Chief of Staff operations |
| `office-hours` | Async Q&A format |
| `skillify` | Convert a prompt into a reusable skill |
| `codex` | Codex-style task runner |
| `benchmark` / `benchmark-models` | Model benchmarking |
| `land-and-deploy` / `setup-deploy` | Deploy workflows |
| `document-generate` / `document-release` | Doc generation and release notes |
| `context-save` / `context-restore` | Save/restore session context |
| `scrape` | Web scraping |
| `browse` / `open-gstack-browser` | Browser automation (requires Playwright) |
| `make-pdf` | Generate PDF from content |
| `sync-gbrain` / `setup-gbrain` | GBrain integration |
| `landing-report` | Landing page analysis |
| `plan-eng-review` / `plan-ceo-review` / `plan-design-review` / `plan-devex-review` / `plan-tune` | Structured plan reviews |
| `ios-fix` / `ios-qa` / `ios-clean` / `ios-sync` / `ios-design-review` | iOS workflows |
| `gstack-upgrade` | Upgrade gstack itself |
