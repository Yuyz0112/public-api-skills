# GET /api/v4/projects/{id}/jobs/{job_id}/artifacts/*artifact_path

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Download a specific file from artifacts archive**
**Operation ID:** `getApiV4ProjectsIdJobsJobIdArtifacts*artifactPath`

This feature was introduced in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `job_id` | path | integer | Yes | The ID of a job |
| `artifact_path` | query | string | Yes | Path to a file inside the artifacts archive. |
| `job_token` | query | string | No | To be used with triggers for multi-project pipelines, available only on Premium and Ultimate tiers. |

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

