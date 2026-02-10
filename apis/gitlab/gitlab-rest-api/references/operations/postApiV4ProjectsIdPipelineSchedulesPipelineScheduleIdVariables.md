# POST /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/variables

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Create a new pipeline schedule variable**
**Operation ID:** `postApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdVariables`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |

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

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

