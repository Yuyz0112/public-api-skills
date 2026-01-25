# GET /admin/api/2021-01/orders/{order_id}/fulfillments/{fulfillment_id}/events/{event_id}.json

**Resource:** [shipping-and-fulfillment/fulfillmentevent](../resources/shipping-and-fulfillment-fulfillmentevent.md)
**Retrieves a specific fulfillment event**
**Operation ID:** `deprecated_202101_get_orders_param_order_id_fulfillments_param_fulfillment_id_events_param_event_id`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentevent#show-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `fulfillment_id` | path | string | Yes | fulfillment_id |
| `event_id` | path | string | Yes | event_id |
| `event_id` | query | any | No | The ID of the fulfillment event. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

