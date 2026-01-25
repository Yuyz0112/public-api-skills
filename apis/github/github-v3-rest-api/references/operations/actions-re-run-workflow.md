# POST /repos/{owner}/{repo}/actions/runs/{run_id}/rerun

**Resource:** [actions](../resources/actions.md)
**Re-run a workflow**
**Operation ID:** `actions/re-run-workflow`

Re-runs your workflow run using its `id`.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

