# POST /repos/{owner}/{repo}/actions/runs/{run_id}/cancel

**Resource:** [actions](../resources/actions.md)
**Cancel a workflow run**
**Operation ID:** `actions/cancel-workflow-run`

Cancels a workflow run using its `id`.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 409 | (reference) |

