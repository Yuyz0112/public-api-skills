# PUT /api/v4/application/plan_limits

**Resource:** [Plan limits](../resources/Plan-limits.md)
**Change plan limits**
**Operation ID:** `putApiV4ApplicationPlanLimits`

Modify the limits of a plan on the GitLab instance.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesPlanLimit](../schemas/APIEntitiesPlanLimit/APIEntitiesPlanLimit.md)

