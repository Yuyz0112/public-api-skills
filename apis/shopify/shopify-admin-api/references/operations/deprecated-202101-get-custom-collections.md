# GET /admin/api/2021-01/custom_collections.json

**Resource:** [products/customcollection](../resources/products-customcollection.md)
**Retrieves a list of custom collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_custom_collections`

https://shopify.dev/docs/admin-api/rest/reference/products/customcollection#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `ids` | query | any | No | Show only collections specified by a comma-separated list of IDs. |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `title` | query | any | No | Show custom collections with a given title. |
| `product_id` | query | any | No | Show custom collections that include a given product. |
| `handle` | query | any | No | Filter by custom collection handle. |
| `updated_at_min` | query | any | No | Show custom collections last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Show custom collections last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_min` | query | any | No | Show custom collections published after date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_max` | query | any | No | Show custom collections published before date (format: 2014-04-25T16:15:47-04:00). |
| `published_status` | query | any | No | Show custom collectsion with a given published status.
                  (default: any)
                    
                        published: Show only published custom collections.
                        unpublished: Show only unpublished custom collections.
                        any: Show custom collections of any published status. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

