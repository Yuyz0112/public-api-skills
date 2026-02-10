# PUT /api/v4/projects/{id}/freeze_periods/{freeze_period_id}

**Resource:** [Freeze periods](../resources/Freeze-periods.md)
**Update a freeze period**
**Operation ID:** `putApiV4ProjectsIdFreezePeriodsFreezePeriodId`

Updates a freeze period for the given `freeze_period_id`. This feature was introduced in GitLab 13.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesFreezePeriod](../schemas/APIEntitiesFreezePeriod/APIEntitiesFreezePeriod.md)

