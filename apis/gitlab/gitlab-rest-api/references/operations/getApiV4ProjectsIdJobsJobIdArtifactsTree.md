# GET /api/v4/projects/{id}/jobs/{job_id}/artifacts/tree

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**List all files in the artifacts archive**
**Operation ID:** `getApiV4ProjectsIdJobsJobIdArtifactsTree`

Lists all files and directories in the artifacts archive without extracting them

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `job_id` | path | integer | Yes | ID of a job |
| `path` | query | string | No | Path to browse in the artifacts archive. Defaults to root directory. |
| `recursive` | query | boolean | No | If `true`, return all entries recursively. |
| `job_token` | query | string | No | CI/CD job token for multi-project pipelines. Premium and Ultimate only. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJobArtifactEntry](../schemas/APIEntitiesCiJobArtifactEntry/APIEntitiesCiJobArtifactEntry.md)

