# POST /admin/api/unstable/orders/{order_id}/refunds.json

**Resource:** [orders/refund](../resources/orders-refund.md)
**Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute.**
**Operation ID:** `deprecated_unstable_create_orders_param_order_id_refunds`

https://shopify.dev/docs/admin-api/rest/reference/orders/refund#create-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `restock
                  deprecated` | query | any | No | Whether to add the line items back to the store inventory. Use restock_type for refund line items instead. |
| `notify` | query | any | No | Whether to send a refund notification to the customer. |
| `note` | query | any | No | An optional note attached to a refund. |
| `discrepancy_reason` | query | any | No | An optional comment that explains a discrepancy between calculated and actual refund amounts. Used to populate the reason property of the resulting order adjustment object attached to the refund. Valid values: restock, damage, customer, and other. |
| `shipping` | query | any | No | Specify how much shipping to refund. It has the following properties:
                    
                        full_refund: Whether to refund all remaining shipping.
                        amount: Set a specific amount to refund for shipping. Takes precedence over full_refund. |
| `refund_line_items` | query | any | No | A list of line item IDs, quantities to refund, and restock instructions. Each entry has the following properties:
                    
                        line_item_id: The ID of a line item to refund.
                        quantity: The quantity to refund.
                        restock_type:           How this refund line item affects inventory levels. Valid values:
          
            no_restock: Refunding these items won't affect inventory.
            cancel: The items have not yet been fulfilled.
            The canceled quantity will be added back to the available count.
            The number of fulfillable units for this line item will decrease.
            return: The items were already delivered but will be returned to the merchant.
            The returned quantity will be added back to the available count. The number of fulfillable units for this
            line item will remain unchanged.
          

                        location_id:           The ID of the location where the items should be
          restocked. This is required when the value of restock_type is return or cancel.
          If the item is not already stocked at the location, then
          the item is connected to the location. An error is returned when the item is connected to
          a 
          fulfillment service location and a different location is provided. |
| `transactions` | query | any | No | A list of transactions
          to process as refunds. |
| `currency` | query | any | No | The three-letter code (ISO 4217 format) for the currency used for the refund. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

