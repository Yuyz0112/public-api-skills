# POST /admin/api/2020-10/orders/{order_id}/refunds/calculate.json

**Resource:** [orders/refund](../resources/orders-refund.md)
**Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted.**
**Operation ID:** `create_orders_param_order_id_refunds_calculate`

https://shopify.dev/docs/admin-api/rest/reference/orders/refund#calculate-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |
| `shipping` | query | any | No | Specify how much shipping to refund. It has the following properties:
                    
                        full_refund: Whether to refund all remaining shipping.
                        amount: Set a specific amount to refund for shipping. Takes precedence over full_refund. |
| `refund_line_items` | query | any | No | A list of line item IDs, quantities to refund, and restock instructions. Each entry has the following properties:
                    
                        line_item_id: The ID of a line item to refund.
                        quantity: The quantity to refund.
                        restock_type:           How this refund line item affects inventory levels. Valid values:
          
            no_restock: Refunding these items won't affect inventory.
            cancel: The items have not yet been fulfilled. The canceled quantity will be added
            back to the available count. The number of fulfillable units for this line item will decrease.
            return: The items were already delivered but will be returned to the merchant.
            The returned quantity will be added back to the available count.
            The number of fulfillable units for this line item will remain unchanged.
          

                        location_id:           The ID of the location
          where the items should be restocked. If location_id is not provided and the value of
          restock_type is return or cancel, then the endpoint returns a suitable
          location ID.

                        already_stocked:           Whether the item is already stocked at
          the location. If this is false, then creating the refund will connect the item to the location and start
          stocking it there. |
| `currency` | query | any | No | The three-letter code (ISO 4217 format) for the
          currency used for the refund. Note: Required whenever the shipping amount property is provided. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

