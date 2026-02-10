# GET /api/v4/projects/{id}/jobs/artifacts/{ref_name}/raw/*artifact_path

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Download a specific file from artifacts archive from a ref**
**Operation ID:** `getApiV4ProjectsIdJobsArtifactsRefNameRaw*artifactPath`

This feature was introduced in GitLab 11.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `ref_name` | path | string | Yes | Branch or tag name in repository. `HEAD` or `SHA` references are not supported. |
| `job` | query | string | Yes | The name of the job. |
| `artifact_path` | query | string | Yes | Path to a file inside the artifacts archive. |
| `job_token` | query | string | No | To be used with triggers for multi-project pipelines, available only on Premium and Ultimate tiers. |

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

