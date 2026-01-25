# GET /admin/api/2020-10/reports.json

**Resource:** [analytics/report](../resources/analytics-report.md)
**Retrieves a list of reports. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `get_reports`

https://shopify.dev/docs/admin-api/rest/reference/analytics/report#index-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | any | No | A comma-separated list of report IDs. |
| `limit` | query | any | No | The amount of results to return.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `updated_at_min` | query | any | No | Show reports last updated after date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Show reports last updated before date. (format: 2014-04-25T16:15:47-04:00) |
| `fields` | query | any | No | A comma-separated list of fields to include in the response. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

