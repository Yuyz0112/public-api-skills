# POST /api/v4/projects/{id}/pipeline_schedules

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Create a new pipeline schedule**
**Operation ID:** `postApiV4ProjectsIdPipelineSchedules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineScheduleDetails](../schemas/APIEntitiesCiPipelineScheduleDetails/APIEntitiesCiPipelineScheduleDetails.md)

