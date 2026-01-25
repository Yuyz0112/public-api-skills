# GET /repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}

**Resource:** [actions](../resources/actions.md)
**Get a workflow run attempt**
**Operation ID:** `actions/get-workflow-run-attempt`

Gets a specific workflow run attempt.

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[workflow-run](../schemas/workflow-run/workflow-run.md)

