# orders/refund

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
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
