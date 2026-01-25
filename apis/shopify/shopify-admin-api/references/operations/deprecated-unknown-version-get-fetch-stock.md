# GET /fetch_stock

**Resource:** [shipping-and-fulfillment/fulfillmentservice](../resources/shipping-and-fulfillment-fulfillmentservice.md)
**Get inventory levels**
**Operation ID:** `deprecated_unknown_version_get_fetch_stock`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentservice#fetch-stock

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `max_retries` | query | any | No | The maximum amount of times Shopify will send the request for inventory levels. |
| `shop` | query | any | No | The shop's myshopify url. |
| `sku` | query | any | No | The SKU for the Product Variant we need stock levels for. |
| `timestamp` | query | any | No | The Unix timestamp from when the inventory request was made. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

