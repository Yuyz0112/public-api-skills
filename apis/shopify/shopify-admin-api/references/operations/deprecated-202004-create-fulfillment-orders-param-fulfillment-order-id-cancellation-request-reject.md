# POST /admin/api/2020-04/fulfillment_orders/{fulfillment_order_id}/cancellation_request/reject.json

**Resource:** [shipping-and-fulfillment/cancellationrequest](../resources/shipping-and-fulfillment-cancellationrequest.md)
**Rejects a cancellation request sent to a fulfillment service for a fulfillment order.**
**Operation ID:** `deprecated_202004_create_fulfillment_orders_param_fulfillment_order_id_cancellation_request_reject`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/cancellationrequest#reject-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `message` | query | any | No | An optional reason for rejecting the cancellation request. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

