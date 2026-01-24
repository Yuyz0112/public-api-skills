# POST /v1/subscription_schedules/{schedule}

**Resource:** [subscription_schedules](../resources/subscription-schedules.md)
**Update a schedule**
**Operation ID:** `PostSubscriptionSchedulesSchedule`

<p>Updates an existing subscription schedule.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schedule` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription_schedule](../schemas/subscription/subscription-schedule.md)

