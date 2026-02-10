# POST /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/play

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Play a scheduled pipeline immediately**
**Operation ID:** `postApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdPlay`

This feature was added in GitLab 12.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

