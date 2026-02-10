# GET /api/v4/application/plan_limits

**Resource:** [Plan limits](../resources/Plan-limits.md)
**Get current plan limits**
**Operation ID:** `getApiV4ApplicationPlanLimits`

List the current limits of a plan on the GitLab instance.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `plan_name` | query | enum: default, free, bronze... | No | Name of the plan to get the limits from. Default: default. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesPlanLimit](../schemas/APIEntitiesPlanLimit/APIEntitiesPlanLimit.md)

