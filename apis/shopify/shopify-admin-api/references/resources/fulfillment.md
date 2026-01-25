# fulfillment

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/deprecated-202001-create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/2020-01/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/deprecated-202001-get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/2020-01/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/deprecated-202001-get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/2020-01/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/deprecated-202001-get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/2020-01/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/deprecated-202001-update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/2020-01/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/deprecated-202001-create-fulfillments.md) |
| POST | `/admin/api/2020-01/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/deprecated-202001-create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/deprecated-202001-create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/deprecated-202001-create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/2020-01/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/deprecated-202001-create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/2020-01/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/deprecated-202001-create-fulfillments-param-fulfillment-id-cancel.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/deprecated-202004-create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/2020-04/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/deprecated-202004-get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/deprecated-202004-get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/2020-04/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/deprecated-202004-get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/2020-04/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/deprecated-202004-update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/2020-04/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/deprecated-202004-create-fulfillments.md) |
| POST | `/admin/api/2020-04/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/deprecated-202004-create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/deprecated-202004-create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/deprecated-202004-create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/2020-04/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/deprecated-202004-create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/2020-04/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/deprecated-202004-create-fulfillments-param-fulfillment-id-cancel.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/deprecated-202007-create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/2020-07/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/deprecated-202007-get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/deprecated-202007-get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/2020-07/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/deprecated-202007-get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/2020-07/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/deprecated-202007-update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/2020-07/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/deprecated-202007-create-fulfillments.md) |
| POST | `/admin/api/2020-07/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/deprecated-202007-create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/deprecated-202007-create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/deprecated-202007-create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/2020-07/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/deprecated-202007-create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/2020-07/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/deprecated-202007-create-fulfillments-param-fulfillment-id-cancel.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/2020-10/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/2020-10/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/create-fulfillments.md) |
| POST | `/admin/api/2020-10/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/2020-10/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/2020-10/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/create-fulfillments-param-fulfillment-id-cancel.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/deprecated-202101-create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/2021-01/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/deprecated-202101-get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/deprecated-202101-get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/2021-01/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/deprecated-202101-get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/2021-01/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/deprecated-202101-update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/2021-01/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/deprecated-202101-create-fulfillments.md) |
| POST | `/admin/api/2021-01/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/deprecated-202101-create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/deprecated-202101-create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/deprecated-202101-create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/2021-01/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/deprecated-202101-create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/2021-01/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/deprecated-202101-create-fulfillments-param-fulfillment-id-cancel.md) |
| GET | `/admin/api/unstable/orders/{order_id}/fulfillments.json` | Retrieves fulfillments associated with an order. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-orders-param-order-id-fulfillments.md) |
| POST | `/admin/api/unstable/orders/{order_id}/fulfillments.json` | Create a fulfillment for the specified order and line items.
          The fulfillment's status depends on the line items in the order:
          
          If the line items in the fulfillment use a manual or custom fulfillment service, then the status of the returned fulfillment will be set immediately.
          If the line items use an external fulfillment service, then they will be queued for fulfillment and the status will be set to pending until the external fulfillment service has been invoked.
          
          
          A fulfillment might then transition to open, which implies it is being processed by the service, before transitioning to success when the items have shipped.
          If you don't specify line item IDs, then all unfulfilled and partially fulfilled line items for the order will be fulfilled.
          However, if an order is refunded or if any of its individual line items are refunded, then the order can't be fulfilled.
          
          All line items being fulfilled must have the same fulfillment service.
          
          
            Note
            If you are using this endpoint with a Partner development store or a trial store, then you can create no more than 5 new fulfillments per minute.
          
          About tracking urls
           If you're creating a fulfillment for a supported carrier, then you can send the tracking_company and tracking_numbers fields, and Shopify will generate the tracking_url for you. If you're creating a fulfillment for an unsupported carrier (not in the tracking_company list), then send the tracking_company, tracking_numbers, and tracking_urls fields.
           
          
            Note
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment. | [View](../operations/deprecated-unstable-create-orders-param-order-id-fulfillments.md) |
| GET | `/admin/api/unstable/fulfillment_orders/{fulfillment_order_id}/fulfillments.json` | Retrieves fulfillments associated with a fulfillment order. | [View](../operations/deprecated-unstable-get-fulfillment-orders-param-fulfillment-order-id-fulfillments.md) |
| GET | `/admin/api/unstable/orders/{order_id}/fulfillments/count.json` | Retrieves a count of fulfillments associated with a specific order | [View](../operations/deprecated-unstable-get-orders-param-order-id-fulfillments-count.md) |
| GET | `/admin/api/unstable/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Retrieve a specific fulfillment | [View](../operations/deprecated-unstable-get-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| PUT | `/admin/api/unstable/orders/{order_id}/fulfillments/{fulfillment_id}.json` | Update information associated with a fulfillment | [View](../operations/deprecated-unstable-update-orders-param-order-id-fulfillments-param-fulfillment-id.md) |
| POST | `/admin/api/unstable/fulfillments.json` | Creates a fulfillment for one or many fulfillment orders. The fulfillment orders are associated with the same order and are assigned to the same location. | [View](../operations/deprecated-unstable-create-fulfillments.md) |
| POST | `/admin/api/unstable/fulfillments/{fulfillment_id}/update_tracking.json` | Updates the tracking information for a fulfillment. | [View](../operations/deprecated-unstable-create-fulfillments-param-fulfillment-id-update-tracking.md) |
| POST | `/admin/api/unstable/orders/{order_id}/fulfillments/{fulfillment_id}/complete.json` | Mark a fulfillment as complete | [View](../operations/deprecated-unstable-create-orders-param-order-id-fulfillments-param-fulfillment-id-complete.md) |
| POST | `/admin/api/unstable/orders/{order_id}/fulfillments/{fulfillment_id}/open.json` | Mark a fulfillment as open | [View](../operations/deprecated-unstable-create-orders-param-order-id-fulfillments-param-fulfillment-id-open.md) |
| POST | `/admin/api/unstable/orders/{order_id}/fulfillments/{fulfillment_id}/cancel.json` | Cancel a fulfillment for a specific order ID | [View](../operations/deprecated-unstable-create-orders-param-order-id-fulfillments-param-fulfillment-id-cancel.md) |
| POST | `/admin/api/unstable/fulfillments/{fulfillment_id}/cancel.json` | Cancels a fulfillment. | [View](../operations/deprecated-unstable-create-fulfillments-param-fulfillment-id-cancel.md) |
