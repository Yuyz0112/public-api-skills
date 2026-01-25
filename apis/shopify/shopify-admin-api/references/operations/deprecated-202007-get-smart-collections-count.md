# GET /admin/api/2020-07/smart_collections/count.json

**Resource:** [products/smartcollection](../resources/products-smartcollection.md)
**Retrieves a count of smart collections**
**Operation ID:** `deprecated_202007_get_smart_collections_count`

https://shopify.dev/docs/admin-api/rest/reference/products/smartcollection#count-2020-07

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `title` | query | any | No | Show smart collections with the specified title. |
| `product_id` | query | any | No | Show smart collections that include the specified product. |
| `updated_at_min` | query | any | No | Show smart collections last updated after this date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Show smart collections last updated before this date.  (format: 2014-04-25T16:15:47-04:00) |
| `published_at_min` | query | any | No | Show smart collections published after this date.  (format: 2014-04-25T16:15:47-04:00) |
| `published_at_max` | query | any | No | Show smart collections published before this date.  (format: 2014-04-25T16:15:47-04:00) |
| `published_status` | query | any | No | Filter results based on the published status of smart collections.
                  (default: any)
                    
                        published: Show only published smart collections.
                        unpublished: Show only unpublished smart collections.
                        any: Show all smart collections. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

