# GET /admin/api/2020-01/collection_listings/{collection_listing_id}/product_ids.json

**Resource:** [sales-channels/collectionlisting](../resources/sales-channels-collectionlisting.md)
**Retrieve product_ids that are published to a collection_id.       Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_collection_listings_param_collection_listing_id_product_ids`

https://shopify.dev/docs/admin-api/rest/reference/sales-channels/collectionlisting#product_ids-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `collection_listing_id` | path | string | Yes | collection_listing_id |
| `limit` | query | any | No | Amount of results
                  (default: 50, maximum: 1000) |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

