# orders

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/deprecated-202001-get-checkouts-count.md) |
| GET | `/admin/api/2020-04/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/deprecated-202004-get-checkouts-count.md) |
| GET | `/admin/api/2020-07/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/deprecated-202007-get-checkouts-count.md) |
| GET | `/admin/api/2020-10/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/get-checkouts-count.md) |
| GET | `/admin/api/2021-01/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/deprecated-202101-get-checkouts-count.md) |
| GET | `/admin/api/unstable/checkouts/count.json` | Retrieves a count of checkouts from the past 90 days | [View](../operations/deprecated-unstable-get-checkouts-count.md) |
| GET | `/admin/api/2020-01/orders.json` | Retrieves a list of orders. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-orders.md) |
| POST | `/admin/api/2020-01/orders.json` | Creates an order. By default, product inventory is not claimed.
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
            If you're using this endpoint with a trial or Partner development store, then you can create no more than 5 new orders per minute. | [View](../operations/deprecated-202001-create-orders.md) |
| GET | `/admin/api/2020-01/orders/{order_id}.json` | Retrieves a specific order | [View](../operations/deprecated-202001-get-orders-param-order-id.md) |
| PUT | `/admin/api/2020-01/orders/{order_id}.json` | Updates an order | [View](../operations/deprecated-202001-update-orders-param-order-id.md) |
| DELETE | `/admin/api/2020-01/orders/{order_id}.json` | Deletes an order. Orders that interact with an online gateway can't be deleted. | [View](../operations/deprecated-202001-delete-orders-param-order-id.md) |
| GET | `/admin/api/2020-01/orders/count.json` | Retrieves an order count | [View](../operations/deprecated-202001-get-orders-count.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/close.json` | Closes an order | [View](../operations/deprecated-202001-create-orders-param-order-id-close.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/open.json` | Re-opens a closed order | [View](../operations/deprecated-202001-create-orders-param-order-id-open.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/cancel.json` | Caution
  For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.

Cancels an order. Orders that have a fulfillment object can't be canceled. | [View](../operations/deprecated-202001-create-orders-param-order-id-cancel.md) |
| GET | `/admin/api/2020-04/orders.json` | Retrieves a list of orders. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-orders.md) |
| POST | `/admin/api/2020-04/orders.json` | Creates an order. By default, product inventory is not claimed.
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
            If you're using this endpoint with a trial or Partner development store, then you can create no more than 5 new orders per minute. | [View](../operations/deprecated-202004-create-orders.md) |
| GET | `/admin/api/2020-04/orders/{order_id}.json` | Retrieves a specific order | [View](../operations/deprecated-202004-get-orders-param-order-id.md) |
| PUT | `/admin/api/2020-04/orders/{order_id}.json` | Updates an order | [View](../operations/deprecated-202004-update-orders-param-order-id.md) |
| DELETE | `/admin/api/2020-04/orders/{order_id}.json` | Deletes an order. Orders that interact with an online gateway can't be deleted. | [View](../operations/deprecated-202004-delete-orders-param-order-id.md) |
| GET | `/admin/api/2020-04/orders/count.json` | Retrieves an order count | [View](../operations/deprecated-202004-get-orders-count.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/close.json` | Closes an order | [View](../operations/deprecated-202004-create-orders-param-order-id-close.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/open.json` | Re-opens a closed order | [View](../operations/deprecated-202004-create-orders-param-order-id-open.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/cancel.json` | Caution
  For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.

Cancels an order. Orders that have a fulfillment object can't be canceled. | [View](../operations/deprecated-202004-create-orders-param-order-id-cancel.md) |
| GET | `/admin/api/2020-07/orders.json` | Retrieves a list of orders. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-orders.md) |
| GET | `/admin/api/2020-01/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-orders-param-order-id-risks.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/deprecated-202001-create-orders-param-order-id-risks.md) |
| GET | `/admin/api/2020-01/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/deprecated-202001-get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/2020-01/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/deprecated-202001-update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/2020-01/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/deprecated-202001-delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-orders-param-order-id-risks.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/deprecated-202004-create-orders-param-order-id-risks.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/deprecated-202004-get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/2020-04/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/deprecated-202004-update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/2020-04/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/deprecated-202004-delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-orders-param-order-id-risks.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/deprecated-202007-create-orders-param-order-id-risks.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/deprecated-202007-get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/2020-07/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/deprecated-202007-update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/2020-07/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/deprecated-202007-delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-orders-param-order-id-risks.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/create-orders-param-order-id-risks.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/2020-10/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/2020-10/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-orders-param-order-id-risks.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/deprecated-202101-create-orders-param-order-id-risks.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/deprecated-202101-get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/2021-01/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/deprecated-202101-update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/2021-01/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/deprecated-202101-delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/unstable/orders/{order_id}/risks.json` | Retrieves a list of all order risks for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-orders-param-order-id-risks.md) |
| POST | `/admin/api/unstable/orders/{order_id}/risks.json` | Creates an order risk for an order | [View](../operations/deprecated-unstable-create-orders-param-order-id-risks.md) |
| GET | `/admin/api/unstable/orders/{order_id}/risks/{risk_id}.json` | Retrieves a single order risk by its ID | [View](../operations/deprecated-unstable-get-orders-param-order-id-risks-param-risk-id.md) |
| PUT | `/admin/api/unstable/orders/{order_id}/risks/{risk_id}.json` | Updates an order risk
          
          
            Note
            You cannot modify an order risk that was created by another application. | [View](../operations/deprecated-unstable-update-orders-param-order-id-risks-param-risk-id.md) |
| DELETE | `/admin/api/unstable/orders/{order_id}/risks/{risk_id}.json` | Deletes an order risk for an order
          
          
            Note
            You cannot delete an order risk that was created by another application. | [View](../operations/deprecated-unstable-delete-orders-param-order-id-risks-param-risk-id.md) |
| GET | `/admin/api/2020-01/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/deprecated-202001-create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/2020-01/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/deprecated-202001-get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/deprecated-202001-create-orders-param-order-id-refunds-calculate.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/deprecated-202004-create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/deprecated-202004-get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/deprecated-202004-create-orders-param-order-id-refunds-calculate.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/deprecated-202007-create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/deprecated-202007-get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/deprecated-202007-create-orders-param-order-id-refunds-calculate.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/create-orders-param-order-id-refunds-calculate.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/deprecated-202101-create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/deprecated-202101-get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/deprecated-202101-create-orders-param-order-id-refunds-calculate.md) |
| GET | `/admin/api/unstable/orders/{order_id}/refunds.json` | Retrieves a list of refunds for an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-orders-param-order-id-refunds.md) |
| POST | `/admin/api/unstable/orders/{order_id}/refunds.json` | Caution
            For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
          
          Creates a refund. Use the calculate endpoint to produce the transactions to submit.
          
          
            Note
            When you use this endpoint with a Partner development store or a trial store, you can create only five refunds per minute. | [View](../operations/deprecated-unstable-create-orders-param-order-id-refunds.md) |
| GET | `/admin/api/unstable/orders/{order_id}/refunds/{refund_id}.json` | Retrieves a specific refund. | [View](../operations/deprecated-unstable-get-orders-param-order-id-refunds-param-refund-id.md) |
| POST | `/admin/api/unstable/orders/{order_id}/refunds/calculate.json` | Caution
          For multi-currency orders, the currency property is required whenever the amount property is provided. For more information, see Migrating to support multiple currencies.
        
          Calculates refund transactions based on line items and shipping. When you want to create a refund,
          you should first use the calculate endpoint to generate accurate refund transactions. Specify the line items
          that are being refunded, their quantity and restock instructions, and whether you intend to refund
          shipping costs. If the restock instructions can't be met—for example, because you try to return more items than have been
          fulfilled—then the endpoint returns modified restock instructions. You can then use the response in the body of the request to create the actual refund.
          The response includes a transactions object with "kind": "suggested_refund",
          which must to be changed to "kind" : "refund" for the refund to be accepted. | [View](../operations/deprecated-unstable-create-orders-param-order-id-refunds-calculate.md) |
