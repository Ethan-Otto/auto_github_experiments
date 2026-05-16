# auto_github_experiments

Sandbox for autonomous agent → GitHub workflows.

## Branches

| Branch  | Purpose                | Direct push           |
|---------|------------------------|-----------------------|
| `dev`   | active development     | humans yes, agents no |
| `staging` | release candidate    | no one (PR only)      |
| `prod`  | production             | no one (PR only)      |

Agents work on `feature/*` branches and open PRs into `dev` (testing) or `staging` (ready).

## Local dev

```bash
uv sync
uv run python -m app
```
