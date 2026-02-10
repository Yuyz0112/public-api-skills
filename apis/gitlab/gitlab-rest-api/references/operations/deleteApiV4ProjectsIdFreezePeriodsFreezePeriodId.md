# DELETE /api/v4/projects/{id}/freeze_periods/{freeze_period_id}

**Resource:** [Freeze periods](../resources/Freeze-periods.md)
**Delete a freeze period**
**Operation ID:** `deleteApiV4ProjectsIdFreezePeriodsFreezePeriodId`

Deletes a freeze period for the given `freeze_period_id`. This feature was introduced in GitLab 13.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `freeze_period_id` | path | integer | Yes | The ID of the freeze period |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |

