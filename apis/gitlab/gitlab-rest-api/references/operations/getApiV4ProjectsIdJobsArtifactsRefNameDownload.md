# GET /api/v4/projects/{id}/jobs/artifacts/{ref_name}/download

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Download the artifacts archive from a job**
**Operation ID:** `getApiV4ProjectsIdJobsArtifactsRefNameDownload`

This feature was introduced in GitLab 8.10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `ref_name` | path | string | Yes | Branch or tag name in repository. `HEAD` or `SHA` references are not supported. |
| `job` | query | string | Yes | The name of the job. |
| `job_token` | query | string | No | To be used with triggers for multi-project pipelines, available only on Premium and Ultimate tiers. |
| `search_recent_successful_pipelines` | query | boolean | No | Search across recent successful pipelines instead of just the latest one. |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

