# GET /admin/api/2020-07/redirects.json

**Resource:** [online-store/redirect](../resources/online-store-redirect.md)
**Retrieves a list of URL redirects. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202007_get_redirects`

https://shopify.dev/docs/admin-api/rest/reference/online-store/redirect#index-2020-07

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `path` | query | any | No | Show redirects with a given path. |
| `target` | query | any | No | Show redirects with a given target. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

