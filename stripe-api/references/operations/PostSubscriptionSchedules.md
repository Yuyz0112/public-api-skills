# POST /v1/subscription_schedules

**Resource:** [subscription_schedules](../resources/subscription-schedules.md)
**Create a schedule**
**Operation ID:** `PostSubscriptionSchedules`

<p>Creates a new subscription schedule object. Each customer can have up to 500 active or scheduled subscriptions.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription_schedule](../schemas/subscription/subscription-schedule.md)

