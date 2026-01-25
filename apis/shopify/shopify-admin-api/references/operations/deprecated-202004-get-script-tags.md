# GET /admin/api/2020-04/script_tags.json

**Resource:** [online-store/scripttag](../resources/online-store-scripttag.md)
**Retrieves a list of all script tags. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202004_get_script_tags`

https://shopify.dev/docs/admin-api/rest/reference/online-store/scripttag#index-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The number of results to return.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `created_at_min` | query | any | No | Show script tags created after this date. (format: 2014-04-25T16:15:47-04:00) |
| `created_at_max` | query | any | No | Show script tags created before this date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_min` | query | any | No | Show script tags last updated after this date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Show script tags last updated before this date. (format: 2014-04-25T16:15:47-04:00) |
| `src` | query | any | No | Show script tags with this URL. |
| `fields` | query | any | No | A comma-separated list of fields to include in the response. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

