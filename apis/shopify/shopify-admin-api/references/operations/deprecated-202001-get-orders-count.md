# GET /admin/api/2020-01/orders/count.json

**Resource:** [orders/order](../resources/orders-order.md)
**Retrieves an order count**
**Operation ID:** `deprecated_202001_get_orders_count`

https://shopify.dev/docs/admin-api/rest/reference/orders/order#count-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_at_min` | query | any | No | Count orders created after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Count orders created before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Count orders last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Count orders last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `status` | query | any | No | Count orders of a given status.
                  (default: open)
                    
                        open: Count open orders.
                        closed: Count closed orders.
                        any: Count orders of any status. |
| `financial_status` | query | any | No | Count orders of a given financial status.
                  (default: any)
                    
                        authorized: Count authorized orders.
                        pending: Count pending orders.
                        paid: Count paid orders.
                        refunded: Count refunded orders.
                        voided: Count voided orders.
                        any: Count orders of any financial status. |
| `fulfillment_status` | query | any | No | Filter orders by their fulfillment status.
                  (default: any)
                    
                        shipped: Show orders that have been shipped. Returns orders with fulfillment_status of fulfilled.
                        partial: Show partially shipped orders.
                        unshipped: Show orders that have not yet been shipped. Returns orders with fulfillment_status of null.
                        any: Show orders of any fulfillment status.
                        unfulfilled: Returns orders with fulfillment_status of null or partial. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

