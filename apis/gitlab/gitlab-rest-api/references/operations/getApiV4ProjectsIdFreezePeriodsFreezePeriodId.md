# GET /api/v4/projects/{id}/freeze_periods/{freeze_period_id}

**Resource:** [Freeze periods](../resources/Freeze-periods.md)
**Get a freeze period**
**Operation ID:** `getApiV4ProjectsIdFreezePeriodsFreezePeriodId`

Get a freeze period for the given `freeze_period_id`. This feature was introduced in GitLab 13.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `freeze_period_id` | path | integer | Yes | The ID of the freeze period |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFreezePeriod](../schemas/APIEntitiesFreezePeriod/APIEntitiesFreezePeriod.md)

