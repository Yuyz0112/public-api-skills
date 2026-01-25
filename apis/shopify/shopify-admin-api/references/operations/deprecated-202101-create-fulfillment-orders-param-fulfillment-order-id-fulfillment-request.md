# POST /admin/api/2021-01/fulfillment_orders/{fulfillment_order_id}/fulfillment_request.json

**Resource:** [shipping-and-fulfillment/fulfillmentrequest](../resources/shipping-and-fulfillment-fulfillmentrequest.md)
**Sends a fulfillment request to the fulfillment service of a fulfillment order.**
**Operation ID:** `deprecated_202101_create_fulfillment_orders_param_fulfillment_order_id_fulfillment_request`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentrequest#create-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `message` | query | any | No | An optional message for the fulfillment request. |
| `fulfillment_order_line_items` | query | any | No | The fulfillment order line items to be requested for fulfillment. If left blank, all line items of the fulfillment order are requested for fulfillment. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

