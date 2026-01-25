# DELETE /repos/{owner}/{repo}/actions/runs/{run_id}/logs

**Resource:** [actions](../resources/actions.md)
**Delete workflow run logs**
**Operation ID:** `actions/delete-workflow-run-logs`

Deletes all logs for a workflow run.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |
| 500 | (reference) |

