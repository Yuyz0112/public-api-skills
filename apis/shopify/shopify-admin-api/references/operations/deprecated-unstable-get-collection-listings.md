# GET /admin/api/unstable/collection_listings.json

**Resource:** [sales-channels/collectionlisting](../resources/sales-channels-collectionlisting.md)
**Retrieve collection listings that are published to your app. Note: As of version 2019-07, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_unstable_get_collection_listings`

https://shopify.dev/docs/admin-api/rest/reference/sales-channels/collectionlisting#index-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | Amount of results
                  (default: 50, maximum: 1000) |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

