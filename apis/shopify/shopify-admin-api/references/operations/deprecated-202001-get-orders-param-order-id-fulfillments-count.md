# GET /admin/api/2020-01/orders/{order_id}/fulfillments/count.json

**Resource:** [shipping-and-fulfillment/fulfillment](../resources/shipping-and-fulfillment-fulfillment.md)
**Retrieves a count of fulfillments associated with a specific order**
**Operation ID:** `deprecated_202001_get_orders_param_order_id_fulfillments_count`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillment#count-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `created_at_min` | query | any | No | Count fulfillments created after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Count fulfillments created before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Count fulfillments last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Count fulfillments last updated before date (format: 2014-04-25T16:15:47-04:00). |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

