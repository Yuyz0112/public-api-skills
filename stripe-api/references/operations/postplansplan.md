# POST /v1/plans/{plan}

**Resource:** [plans](../resources/plans.md)
**Update a plan**
**Operation ID:** `PostPlansPlan`

<p>Updates the specified plan by setting the values of the parameters passed. Any parameters not provided are left unchanged. By design, you cannot change a plan’s ID, amount, currency, or billing cycle.</p>

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

[plan](../schemas/plan/plan.md)

