# POST /repos/{owner}/{repo}/actions/runs/{run_id}/rerun-failed-jobs

**Resource:** [actions](../resources/actions.md)
**Re-run failed jobs from a workflow run**
**Operation ID:** `actions/re-run-workflow-failed-jobs`

Re-run all of the failed jobs and their dependent jobs in a workflow run using the `id` of the workflow run.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

