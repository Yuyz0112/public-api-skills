# GET /api/v4/projects/{id}/jobs/{job_id}/trace

**Resource:** [CI jobs](../resources/CI-jobs.md)
**Get a trace of a specific job of a project**
**Operation ID:** `getApiV4ProjectsIdJobsJobIdTrace`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `job_id` | path | integer | Yes | The ID of a job |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)

