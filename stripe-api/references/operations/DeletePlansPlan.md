# DELETE /v1/plans/{plan}

**Resource:** [plans](../resources/plans.md)
**Delete a plan**
**Operation ID:** `DeletePlansPlan`

<p>Deleting plans means new subscribers can’t be added. Existing subscribers aren’t affected.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `plan` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_plan](../schemas/deleted/deleted-plan.md)

