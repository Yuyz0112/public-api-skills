# GET /admin/api/2020-04/orders/{order_id}/fulfillments/{fulfillment_id}/events.json

**Resource:** [shipping-and-fulfillment/fulfillmentevent](../resources/shipping-and-fulfillment-fulfillmentevent.md)
**Retrieves a list of fulfillment events for a specific fulfillment**
**Operation ID:** `deprecated_202004_get_orders_param_order_id_fulfillments_param_fulfillment_id_events`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentevent#index-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `fulfillment_id` | path | string | Yes | fulfillment_id |
| `fulfillment_id` | query | any | No | The ID of the fulfillment that's associated with the fulfillment event. |
| `order_id` | query | any | No | The ID of the order that's associated with the fulfillment event. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

