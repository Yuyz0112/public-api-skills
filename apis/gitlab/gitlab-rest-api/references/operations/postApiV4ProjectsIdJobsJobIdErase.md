# POST /api/v4/projects/{id}/jobs/{job_id}/erase

**Resource:** [CI jobs](../resources/CI-jobs.md)
**Erase job (remove artifacts and the trace)**
**Operation ID:** `postApiV4ProjectsIdJobsJobIdErase`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `job_id` | path | integer | Yes | The ID of a build |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Conflict |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)

