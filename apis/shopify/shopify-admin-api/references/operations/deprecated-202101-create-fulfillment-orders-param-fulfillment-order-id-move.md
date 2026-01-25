# POST /admin/api/2021-01/fulfillment_orders/{fulfillment_order_id}/move.json

**Resource:** [shipping-and-fulfillment/fulfillmentorder](../resources/shipping-and-fulfillment-fulfillmentorder.md)
**Moves a fulfillment order from one merchant managed location to another merchant managed location.**
**Operation ID:** `deprecated_202101_create_fulfillment_orders_param_fulfillment_order_id_move`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentorder#move-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `new_location_id` | query | any | No | The id of the location to which the fulfillment order will be moved. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

