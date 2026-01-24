# POST /v1/plans

**Resource:** [plans](../resources/plans.md)
**Create a plan**
**Operation ID:** `PostPlans`

<p>You can now model subscriptions more flexibly using the <a href="#prices">Prices API</a>. It replaces the Plans API and is backwards compatible to simplify your migration.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[plan](../schemas/plan/plan.md)

