# GET /admin/api/2020-04/custom_collections/count.json

**Resource:** [products/customcollection](../resources/products-customcollection.md)
**Retrieves a count of custom collections**
**Operation ID:** `deprecated_202004_get_custom_collections_count`

https://shopify.dev/docs/admin-api/rest/reference/products/customcollection#count-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `title` | query | any | No | Count custom collections with given title. |
| `product_id` | query | any | No | Count custom collections that include a given product. |
| `updated_at_min` | query | any | No | Count custom collections last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Count custom collections last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_min` | query | any | No | Count custom collections published after date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_max` | query | any | No | Count custom collections published before date (format: 2014-04-25T16:15:47-04:00). |
| `published_status` | query | any | No | Count custom collections with a given published status.
                  (default: any)
                    
                        published: Count only published custom collections.
                        unpublished: Count only unpublished custom collections.
                        any: Count custom collections of any published status. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

