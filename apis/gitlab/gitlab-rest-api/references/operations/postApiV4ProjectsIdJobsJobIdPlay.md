# POST /api/v4/projects/{id}/jobs/{job_id}/play

**Resource:** [CI jobs](../resources/CI-jobs.md)
**Trigger an actionable job (manual, delayed, etc)**
**Operation ID:** `postApiV4ProjectsIdJobsJobIdPlay`

This feature was added in GitLab 8.11

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `job_id` | path | integer | Yes | The ID of a Job |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJobBasic](../schemas/APIEntitiesCiJobBasic/APIEntitiesCiJobBasic.md)

