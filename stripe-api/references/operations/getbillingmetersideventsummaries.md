# GET /v1/billing/meters/{id}/event_summaries

**Resource:** [billing](../resources/billing.md)
**List billing meter event summaries**
**Operation ID:** `GetBillingMetersIdEventSummaries`

<p>Retrieve a list of billing meter event summaries.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | query | string | Yes | The customer for which to fetch event summaries. |
| `end_time` | query | integer (unix-time) | Yes | The timestamp from when to stop aggregating meter events (exclusive). Must be aligned with minute boundaries. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | Unique identifier for the object. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `start_time` | query | integer (unix-time) | Yes | The timestamp from when to start aggregating meter events (inclusive). Must be aligned with minute boundaries. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `value_grouping_window` | query | enum: day, hour | No | Specifies what granularity to use when generating event summaries. If not specified, a single event summary would be returned for the specified time range. For hourly granularity, start and end times must align with hour boundaries (e.g., 00:00, 01:00, ..., 23:00). For daily granularity, start and end times must align with UTC day boundaries (00:00 UTC). |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

