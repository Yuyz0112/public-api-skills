# GET /admin/api/2021-01/collects.json

**Resource:** [products/collect](../resources/products-collect.md)
**Retrieves a list of collects. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_collects`

https://shopify.dev/docs/admin-api/rest/reference/products/collect#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to show.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

