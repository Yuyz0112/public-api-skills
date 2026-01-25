# GET /admin/api/2020-04/product_listings.json

**Resource:** [sales-channels/productlisting](../resources/sales-channels-productlisting.md)
**Retrieve product listings that are published to your app. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202004_get_product_listings`

https://shopify.dev/docs/admin-api/rest/reference/sales-channels/productlisting#index-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `product_ids` | query | any | No | A comma-separated list of product ids |
| `limit` | query | any | No | Amount of results
                  (default: 50, maximum: 1000) |
| `collection_id` | query | any | No | Filter by products belonging to a particular collection |
| `updated_at_min` | query | any | No | Filter by products last updated after a certain date and time (formatted in ISO 8601) |
| `handle` | query | any | No | Filter by product handle |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

