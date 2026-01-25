# GET /admin/api/2020-01/orders.json

**Resource:** [orders/order](../resources/orders-order.md)
**Retrieves a list of orders. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_orders`

https://shopify.dev/docs/admin-api/rest/reference/orders/order#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | any | No | Retrieve only orders specified by a comma-separated list of order IDs. |
| `limit` | query | any | No | The maximum number of results to show on a page.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Show orders after the specified ID. |
| `created_at_min` | query | any | No | Show orders created at or after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Show orders created at or before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Show orders last updated at or after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Show orders last updated at or before date (format: 2014-04-25T16:15:47-04:00). |
| `processed_at_min` | query | any | No | Show orders imported at or after date (format: 2014-04-25T16:15:47-04:00). |
| `processed_at_max` | query | any | No | Show orders imported at or before date (format: 2014-04-25T16:15:47-04:00). |
| `attribution_app_id` | query | any | No | Show orders attributed to a certain app, specified by the app ID. Set as current to show orders for the app currently consuming the API. |
| `status` | query | any | No | Filter orders by their status.
                  (default: open)
                    
                        open: Show only open orders.
                        closed: Show only closed orders.
                        cancelled: Show only canceled orders.
                        any: Show orders of any status, including archived orders. |
| `financial_status` | query | any | No | Filter orders by their financial status.
                  (default: any)
                    
                        authorized: Show only authorized orders
                        pending: Show only pending orders
                        paid: Show only paid orders
                        partially_paid: Show only partially paid orders
                        refunded: Show only refunded orders
                        voided: Show only voided orders
                        partially_refunded: Show only partially refunded orders
                        any: Show orders of any financial status.
                        unpaid: Show authorized and partially paid orders. |
| `fulfillment_status` | query | any | No | Filter orders by their fulfillment status.
                  (default: any)
                    
                        shipped: Show orders that have been shipped. Returns orders with fulfillment_status of fulfilled.
                        partial: Show partially shipped orders.
                        unshipped: Show orders that have not yet been shipped. Returns orders with fulfillment_status of null.
                        any: Show orders of any fulfillment status.
                        unfulfilled: Returns orders with fulfillment_status of null or partial. |
| `fields` | query | any | No | Retrieve only certain fields, specified by a comma-separated list of fields names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

