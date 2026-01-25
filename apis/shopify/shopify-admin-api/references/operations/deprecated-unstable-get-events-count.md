# GET /admin/api/unstable/events/count.json

**Resource:** [events/event](../resources/events-event.md)
**Retrieves a count of events**
**Operation ID:** `deprecated_unstable_get_events_count`

https://shopify.dev/docs/admin-api/rest/reference/events/event#count-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_at_min` | query | any | No | Count only events created at or after this date and time. (format: 2014-04-25T16:15:47-04:00) |
| `created_at_max` | query | any | No | Count only events created at or before this date and time. (format: 2014-04-25T16:15:47-04:00) |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

