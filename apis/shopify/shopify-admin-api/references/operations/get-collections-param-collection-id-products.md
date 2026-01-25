# GET /admin/api/2020-10/collections/{collection_id}/products.json

**Resource:** [products/collection](../resources/products-collection.md)
**Retrieve a list of products belonging to a collection. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.. The products returned are sorted by the collection's sort order.**
**Operation ID:** `get_collections_param_collection_id_products`

https://shopify.dev/docs/admin-api/rest/reference/products/collection#products-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `collection_id` | path | string | Yes | collection_id |
| `limit` | query | any | No | The number of products to retrieve.
                  (default: 50, maximum: 250) |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

