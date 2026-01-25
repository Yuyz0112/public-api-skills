# POST /admin/api/unstable/orders/{order_id}/fulfillments.json

**Resource:** [shipping-and-fulfillment/fulfillment](../resources/shipping-and-fulfillment-fulfillment.md)
**Create a fulfillment for the specified order and line items.
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
            If you send an unsupported carrier without a tracking URL, then Shopify will still try to generate a valid tracking URL by using pattern matching on the tracking number. However, Shopify does not validate the tracking URL, so you should make sure that your tracking URL is correct for the order and fulfillment.**
**Operation ID:** `deprecated_unstable_create_orders_param_order_id_fulfillments`

https://shopify.dev/docs/admin-api/rest/reference/shipping-and-fulfillment/fulfillment#create-unstable

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_id` | path | string | Yes | order_id |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

