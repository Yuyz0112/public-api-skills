# DELETE /api/v4/projects/{id}/jobs/{job_id}/artifacts

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Delete the artifacts files from a job**
**Operation ID:** `deleteApiV4ProjectsIdJobsJobIdArtifacts`

This feature was introduced in GitLab 11.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `job_id` | path | integer | Yes | The ID of a job |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 409 | Conflict |

