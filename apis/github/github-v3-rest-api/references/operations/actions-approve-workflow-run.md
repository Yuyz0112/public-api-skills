# POST /repos/{owner}/{repo}/actions/runs/{run_id}/approve

**Resource:** [actions](../resources/actions.md)
**Approve a workflow run for a fork pull request**
**Operation ID:** `actions/approve-workflow-run`

Approves a workflow run for a pull request from a public fork of a first time contributor. For more information, see ["Approving workflow runs from public forks](https://docs.github.com/actions/managing-workflow-runs/approving-workflow-runs-from-public-forks)."

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

