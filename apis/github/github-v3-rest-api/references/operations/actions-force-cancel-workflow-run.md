# POST /repos/{owner}/{repo}/actions/runs/{run_id}/force-cancel

**Resource:** [actions](../resources/actions.md)
**Force cancel a workflow run**
**Operation ID:** `actions/force-cancel-workflow-run`

Cancels a workflow run and bypasses conditions that would otherwise cause a workflow execution to continue, such as an `always()` condition on a job.
You should only use this endpoint to cancel a workflow run when the workflow run is not responding to [`POST /repos/{owner}/{repo}/actions/runs/{run_id}/cancel`](/rest/actions/workflow-runs#cancel-a-workflow-run).

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 409 | (reference) |

