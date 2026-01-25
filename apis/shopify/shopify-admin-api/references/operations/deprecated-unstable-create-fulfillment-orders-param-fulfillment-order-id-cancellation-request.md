# POST /admin/api/unstable/fulfillment_orders/{fulfillment_order_id}/cancellation_request.json

**Resource:** [shipping-and-fulfillment/cancellationrequest](../resources/shipping-and-fulfillment-cancellationrequest.md)
**Sends a cancellation request to the fulfillment service of a fulfillment order.**
**Operation ID:** `deprecated_unstable_create_fulfillment_orders_param_fulfillment_order_id_cancellation_request`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/cancellationrequest#create-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `message` | query | any | No | An optional reason for the cancellation request. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

