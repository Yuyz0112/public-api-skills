# POST /repos/{owner}/{repo}/actions/jobs/{job_id}/rerun

**Resource:** [actions](../resources/actions.md)
**Re-run a job from a workflow run**
**Operation ID:** `actions/re-run-job-for-workflow-run`

Re-run a job and its dependent jobs in a workflow run.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |

**Success Response Schema:**

[empty-object](../schemas/empty-object/empty-object.md)

