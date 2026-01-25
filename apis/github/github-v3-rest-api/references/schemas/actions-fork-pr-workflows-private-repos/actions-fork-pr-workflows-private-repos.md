# actions-fork-pr-workflows-private-repos

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `run_workflows_from_fork_pull_requests` | boolean | Yes | Whether workflows triggered by pull requests from forks are allowed to run on private repositories. |
| `send_write_tokens_to_workflows` | boolean | Yes | Whether GitHub Actions can create pull requests or submit approving pull request reviews from a workflow triggered by a fork pull request. |
| `send_secrets_and_variables` | boolean | Yes | Whether to make secrets and variables available to workflows triggered by pull requests from forks. |
| `require_approval_for_fork_pr_workflows` | boolean | Yes | Whether workflows triggered by pull requests from forks require approval from a repository administrator to run. |

