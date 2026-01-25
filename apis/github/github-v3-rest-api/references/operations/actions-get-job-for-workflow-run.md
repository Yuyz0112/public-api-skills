# GET /repos/{owner}/{repo}/actions/jobs/{job_id}

**Resource:** [actions](../resources/actions.md)
**Get a job for a workflow run**
**Operation ID:** `actions/get-job-for-workflow-run`

Gets a specific job in a workflow run.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[job](../schemas/job/job.md)

