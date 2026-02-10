# POST /api/v4/projects/{id}/jobs/{job_id}/retry

**Resource:** [CI jobs](../resources/CI-jobs.md)
**Retry a specific job of a project**
**Operation ID:** `postApiV4ProjectsIdJobsJobIdRetry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `job_id` | path | integer | Yes | The ID of a job |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)

