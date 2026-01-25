# GET /admin/api/2021-01/products/count.json

**Resource:** [products/product](../resources/products-product.md)
**Retrieves a count of products.**
**Operation ID:** `deprecated_202101_get_products_count`

https://shopify.dev/docs/admin-api/rest/reference/products/product#count-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `vendor` | query | any | No | Filter results by product vendor. |
| `product_type` | query | any | No | Filter results by product type. |
| `collection_id` | query | any | No | Filter results by collection ID. |
| `created_at_min` | query | any | No | Show products created after date. (format: 2014-04-25T16:15:47-04:00) |
| `created_at_max` | query | any | No | Show products created before date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_min` | query | any | No | Show products last updated after date. (format: 2014-04-25T16:15:47-04:00) |
| `updated_at_max` | query | any | No | Show products last updated before date. (format: 2014-04-25T16:15:47-04:00) |
| `published_at_min` | query | any | No | Show products published after date. (format: 2014-04-25T16:15:47-04:00) |
| `published_at_max` | query | any | No | Show products published before date. (format: 2014-04-25T16:15:47-04:00) |
| `published_status` | query | any | No | Return products by their published status
                  (default: any)
                    
                        published: Show only published products.
                        unpublished: Show only unpublished products.
                        any: Show all products. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

