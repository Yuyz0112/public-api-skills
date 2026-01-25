# GET /admin/api/2020-10/orders/{order_id}/refunds.json

**Resource:** [orders/refund](../resources/orders-refund.md)
**Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `get_orders_param_order_id_refunds`

https://shopify.dev/docs/admin-api/rest/reference/orders/refund#index-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |
| `in_shop_currency` | query | any | No | Show amounts in the shop currency for the underlying transaction.
                  (default: false) |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

