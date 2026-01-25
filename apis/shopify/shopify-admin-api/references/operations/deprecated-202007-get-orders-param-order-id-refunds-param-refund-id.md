# GET /admin/api/2020-07/orders/{order_id}/refunds/{refund_id}.json

**Resource:** [orders/refund](../resources/orders-refund.md)
**Retrieves a specific refund.**
**Operation ID:** `deprecated_202007_get_orders_param_order_id_refunds_param_refund_id`

https://shopify.dev/docs/admin-api/rest/reference/orders/refund#show-2020-07

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `refund_id` | path | string | Yes | refund_id |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |
| `in_shop_currency` | query | any | No | Show amounts in the shop currency for the underlying transaction.
                  (default: false) |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

