# PUT /admin/api/unstable/smart_collections/{smart_collection_id}/order.json

**Resource:** [products/smartcollection](../resources/products-smartcollection.md)
**Updates the ordering type of products in a smart collection**
**Operation ID:** `deprecated_unstable_update_smart_collections_param_smart_collection_id_order`

https://shopify.dev/docs/admin-api/rest/reference/products/smartcollection#order-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `smart_collection_id` | path | string | Yes | smart_collection_id |
| `products` | query | any | No | An array of product IDs, in the order that you want them to appear at the top of the collection. When products is specified but empty, any previously sorted products are cleared. |
| `sort_order` | query | any | No | The type of sorting to apply. Valid values are listed in the Properties section above.
                  (default: (current value)) |
| `products[]` | query | integer | No | products[] |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

