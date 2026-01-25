# GET /v1/subscription_schedules

**Resource:** [subscription_schedules](../resources/subscription-schedules.md)
**List all schedules**
**Operation ID:** `GetSubscriptionSchedules`

<p>Retrieves the list of your subscription schedules.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `canceled_at` | query | any | No | Only return subscription schedules that were created canceled the given date interval. |
| `completed_at` | query | any | No | Only return subscription schedules that completed during the given date interval. |
| `created` | query | any | No | Only return subscription schedules that were created during the given date interval. |
| `customer` | query | string | No | Only return subscription schedules for the given customer. |
| `customer_account` | query | string | No | Only return subscription schedules for the given account. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `released_at` | query | any | No | Only return subscription schedules that were released during the given date interval. |
| `scheduled` | query | boolean | No | Only return subscription schedules that have not started yet. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

