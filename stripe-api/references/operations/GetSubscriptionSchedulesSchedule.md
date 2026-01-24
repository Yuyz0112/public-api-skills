# GET /v1/subscription_schedules/{schedule}

**Resource:** [subscription_schedules](../resources/subscription-schedules.md)
**Retrieve a schedule**
**Operation ID:** `GetSubscriptionSchedulesSchedule`

<p>Retrieves the details of an existing subscription schedule. You only need to supply the unique subscription schedule identifier that was returned upon subscription schedule creation.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

