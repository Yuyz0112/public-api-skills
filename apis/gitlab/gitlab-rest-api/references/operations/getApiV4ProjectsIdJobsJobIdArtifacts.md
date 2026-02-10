# GET /api/v4/projects/{id}/jobs/{job_id}/artifacts

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Download the artifacts archive from a job**
**Operation ID:** `getApiV4ProjectsIdJobsJobIdArtifacts`

This feature was introduced in GitLab 8.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `job_id` | path | integer | Yes | The ID of a job |
| `job_token` | query | string | No | To be used with triggers for multi-project pipelines, available only on Premium and Ultimate tiers. |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

