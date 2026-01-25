# GET /admin/api/unstable/fulfillment_orders/{fulfillment_order_id}/locations_for_move.json

**Resource:** [shipping-and-fulfillment/locationsformove](../resources/shipping-and-fulfillment-locationsformove.md)
**Retrieves a list of locations that a fulfillment order can potentially move to.
          The resulting list is sorted alphabetically in ascending order by location name.**
**Operation ID:** `deprecated_unstable_get_fulfillment_orders_param_fulfillment_order_id_locations_for_move`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/locationsformove#index-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `fulfillment_order_id` | query | any | No | The ID of the fulfillment order. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

