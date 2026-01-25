# POST /admin/api/unstable/fulfillment_orders/{fulfillment_order_id}/fulfillment_request/reject.json

**Resource:** [shipping-and-fulfillment/fulfillmentrequest](../resources/shipping-and-fulfillment-fulfillmentrequest.md)
**Rejects a fulfillment request sent to a fulfillment service for a fulfillment order.**
**Operation ID:** `deprecated_unstable_create_fulfillment_orders_param_fulfillment_order_id_fulfillment_request_reject`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentrequest#reject-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `message` | query | any | No | An optional reason for rejecting the fulfillment request. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

