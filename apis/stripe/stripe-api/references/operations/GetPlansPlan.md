# GET /v1/plans/{plan}

**Resource:** [plans](../resources/plans.md)
**Retrieve a plan**
**Operation ID:** `GetPlansPlan`

<p>Retrieves the plan with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

