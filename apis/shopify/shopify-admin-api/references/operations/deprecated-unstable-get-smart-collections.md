# GET /admin/api/unstable/smart_collections.json

**Resource:** [products/smartcollection](../resources/products-smartcollection.md)
**Retrieves a list of smart collections. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_unstable_get_smart_collections`

https://shopify.dev/docs/admin-api/rest/reference/products/smartcollection#index-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The number of results to show.
                  (default: 50, maximum: 250) |
| `ids` | query | any | No | Show only the smart collections specified by a comma-separated list of IDs. |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `title` | query | any | No | Show smart collections with the specified title. |
| `product_id` | query | any | No | Show smart collections that includes the specified product. |
| `handle` | query | any | No | Filter results by smart collection handle. |
| `updated_at_min` | query | any | No | Show smart collections last updated after this date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Show smart collections last updated before this date. (format: 2014-04-25T16:15:47-04:00) |
| `published_at_min` | query | any | No | Show smart collections published after this date. (format: 2014-04-25T16:15:47-04:00) |
| `published_at_max` | query | any | No | Show smart collections published before this date. (format: 2014-04-25T16:15:47-04:00) |
| `published_status` | query | any | No | Filter results based on the published status of smart collections.
                  (default: any)
                    
                        published: Show only published smart collections.
                        unpublished: Show only unpublished smart collections.
                        any: Show all smart collections. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

