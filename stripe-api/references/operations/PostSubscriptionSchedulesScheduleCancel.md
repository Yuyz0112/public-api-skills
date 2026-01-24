# POST /v1/subscription_schedules/{schedule}/cancel

**Resource:** [subscription_schedules](../resources/subscription-schedules.md)
**Cancel a schedule**
**Operation ID:** `PostSubscriptionSchedulesScheduleCancel`

<p>Cancels a subscription schedule and its associated subscription immediately (if the subscription schedule has an active subscription). A subscription schedule can only be canceled if its status is <code>not_started</code> or <code>active</code>.</p>

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

