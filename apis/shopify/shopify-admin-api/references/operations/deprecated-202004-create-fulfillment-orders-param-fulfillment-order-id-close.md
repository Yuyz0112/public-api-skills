# POST /admin/api/2020-04/fulfillment_orders/{fulfillment_order_id}/close.json

**Resource:** [shipping-and-fulfillment/fulfillmentorder](../resources/shipping-and-fulfillment-fulfillmentorder.md)
**Marks an in progress fulfillment order as incomplete, indicating the fulfillment service
        is unable to ship any remaining items and intends to close the fulfillment order.**
**Operation ID:** `deprecated_202004_create_fulfillment_orders_param_fulfillment_order_id_close`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillmentorder#close-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fulfillment_order_id` | path | string | Yes | fulfillment_order_id |
| `message` | query | any | No | An optional reason for marking the fulfillment order as incomplete. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

