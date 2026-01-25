# GET /admin/api/unstable/assigned_fulfillment_orders.json

**Resource:** [shipping-and-fulfillment/assignedfulfillmentorder](../resources/shipping-and-fulfillment-assignedfulfillmentorder.md)
**Retrieves a list of fulfillment orders on a shop for a specific app.**
**Operation ID:** `deprecated_unstable_get_assigned_fulfillment_orders`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/assignedfulfillmentorder#index-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `assignment_status` | query | any | No | The assigment status of the fulfillment orders that should be returned:
                    
                        cancellation_requested: Fulfillment orders for which the merchant has requested cancellation of the previously accepted fulfillment request.
                        fulfillment_requested: Fulfillment orders for which the merchant has requested fulfillment.
                        fulfillment_accepted: Fulfillment orders for which the merchant's fulfillment request has been accepted. Any number of fulfillments can be created on these fulfillment orders to completely fulfill the requested items. |
| `location_ids` | query | any | No | The IDs of the assigned locations of the fulfillment orders that should be returned. |
| `location_ids[]` | query | integer | No | location_ids[] |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

