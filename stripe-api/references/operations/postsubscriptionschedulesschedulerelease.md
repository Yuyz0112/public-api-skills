# POST /v1/subscription_schedules/{schedule}/release

**Resource:** [subscription_schedules](../resources/subscription-schedules.md)
**Release a schedule**
**Operation ID:** `PostSubscriptionSchedulesScheduleRelease`

<p>Releases the subscription schedule immediately, which will stop scheduling of its phases, but leave any existing subscription in place. A schedule can only be released if its status is <code>not_started</code> or <code>active</code>. If the subscription schedule is currently associated with a subscription, releasing it will remove its <code>subscription</code> property and set the subscription’s ID to the <code>released_subscription</code> property.</p>

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

