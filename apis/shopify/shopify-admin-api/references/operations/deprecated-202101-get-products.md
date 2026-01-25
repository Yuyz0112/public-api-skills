# GET /admin/api/2021-01/products.json

**Resource:** [products/product](../resources/products-product.md)
**Retrieves a list of products. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_products`

https://shopify.dev/docs/admin-api/rest/reference/products/product#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | any | No | Return only products specified by a comma-separated list of product IDs. |
| `limit` | query | any | No | Return up to this many results per page.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `title` | query | any | No | Filter results by product title. |
| `vendor` | query | any | No | Filter results by product vendor. |
| `handle` | query | any | No | Filter results by product handle. |
| `product_type` | query | any | No | Filter results by product type. |
| `status` | query | any | No | Return products by their status.
                  (default: active)
                    
                        active: Show only active products.
                        archived: Show only archived products.
                        draft: Show only draft products. |
| `collection_id` | query | any | No | Filter results by product collection ID. |
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
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |
| `presentment_currencies` | query | any | No | Return presentment prices in only certain currencies, specified by a comma-separated list of ISO 4217 currency codes. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

