# GET /admin/api/2021-01/orders/{order_id}/fulfillments.json

**Resource:** [shipping-and-fulfillment/fulfillment](../resources/shipping-and-fulfillment-fulfillment.md)
**Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_orders_param_order_id_fulfillments`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillment#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `created_at_max` | query | any | No | Show fulfillments created before date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_min` | query | any | No | Show fulfillments created after date (format: 2014-04-25T16:15:47-04:00). |
| `fields` | query | any | No | A comma-separated list of fields to include in the response. |
| `limit` | query | any | No | Limit the amount of results.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `updated_at_max` | query | any | No | Show fulfillments last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Show fulfillments last updated after date (format: 2014-04-25T16:15:47-04:00). |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

