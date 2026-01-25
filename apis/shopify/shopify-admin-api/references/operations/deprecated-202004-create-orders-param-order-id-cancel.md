# POST /admin/api/2020-04/orders/{order_id}/cancel.json

**Resource:** [orders/order](../resources/orders-order.md)
**Caution
  For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.

Cancels an order. Orders that have a fulfillment object can't be canceled.**
**Operation ID:** `deprecated_202004_create_orders_param_order_id_cancel`

https://shopify.dev/docs/admin-api/rest/reference/orders/order#cancel-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `amount` | query | any | No | The amount to refund. If set, Shopify attempts to void or refund the payment, depending on its status. Shopify refunds through a manual gateway in cases where the original transaction was not made in Shopify. Refunds through a manual gateway are recorded as a refund on Shopify, but the customer is not refunded. |
| `currency` | query | any | No | The currency of the refund that's issued when the order is canceled. Required for multi-currency orders whenever the amount property is provided. |
| `restock
                  deprecated` | query | any | No | Whether to restock refunded items back to your store's inventory.
                  (default: false) |
| `reason` | query | any | No | The reason for the order cancellation. Valid values: customer, inventory, fraud, declined, and other.)
                  (default: other) |
| `email` | query | any | No | Whether to send an email to the customer notifying them of the cancellation.
                  (default: false) |
| `refund` | query | any | No | The refund transactions to perform. Required for some more complex refund situations. For more information, see the Refund API. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

