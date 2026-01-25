# POST /admin/api/2020-01/orders.json

**Resource:** [orders/order](../resources/orders-order.md)
**Creates an order. By default, product inventory is not claimed.
          When you create an order, you can include the following option parameters in the body of the request:
          
            inventory_behaviour: The behaviour to use when updating inventory. (default: bypass)
              
                bypass: Do not claim inventory.
                decrement_ignoring_policy: Ignore the product's inventory policy and claim inventory.
                decrement_obeying_policy: Follow the product's inventory policy and claim inventory, if possible.
              
            
            send_receipt: Whether to send an order confirmation to the customer.
            
            
              Note
              If you're working on a private app and order confirmations are still being sent to the customer when send_receipt is set to false, then you need to disable the Storefront API from the private app's page in the Shopify admin.
            
            
            send_fulfillment_receipt: Whether to send a shipping confirmation to the customer.
          
          
            Note
            If you are including shipping_address or billing_address, make sure to pass both
              first_name and last_name. Otherwise both these addresses will be ignored.
            If you're using this endpoint with a trial or Partner development store, then you can create no more than 5 new orders per minute.**
**Operation ID:** `deprecated_202001_create_orders`

https://shopify.dev/docs/admin-api/rest/reference/orders/order#create-2020-01

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

