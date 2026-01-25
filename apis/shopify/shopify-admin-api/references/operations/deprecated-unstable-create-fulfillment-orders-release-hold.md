# POST /admin/api/unstable/fulfillment_orders/release_hold.json

**Resource:** [shipping-and-fulfillment/fulfillmentorder](../resources/shipping-and-fulfillment-fulfillmentorder.md)
**Releases the fulfillment order holds for a specific order. Fulfillment orders are created
          with an ON_HOLD status if the channel that created the order has a fulfillment hold policy.**
**Operation ID:** `deprecated_unstable_create_fulfillment_orders_release_hold`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentorder#release_hold-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | query | any | No | The ID of the order that is associated to the fulfillment orders. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

