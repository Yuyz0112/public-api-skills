# POST /api/v4/projects/{id}/jobs/{job_id}/artifacts/keep

**Resource:** [Job artifacts](../resources/Job-artifacts.md)
**Keep the artifacts to prevent them from being deleted**
**Operation ID:** `postApiV4ProjectsIdJobsJobIdArtifactsKeep`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `job_id` | path | integer | Yes | The ID of a job |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)

