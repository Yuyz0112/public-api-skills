# GET /admin/api/2021-01/events.json

**Resource:** [events/event](../resources/events-event.md)
**Retrieves a list of events. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_events`

https://shopify.dev/docs/admin-api/rest/reference/events/event#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The number of results to show.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Show only results after the specified ID. |
| `created_at_min` | query | any | No | Show events created at or after this date and time. (format: 2014-04-25T16:15:47-04:00) |
| `created_at_max` | query | any | No | Show events created at or before this date and time. (format: 2014-04-25T16:15:47-04:00) |
| `filter` | query | any | No | Show events specified in this filter. |
| `verb` | query | any | No | Show events of a certain type. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

