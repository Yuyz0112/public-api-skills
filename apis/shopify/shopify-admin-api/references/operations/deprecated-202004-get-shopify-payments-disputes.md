# GET /admin/api/2020-04/shopify_payments/disputes.json

**Resource:** [shopify_payments/dispute](../resources/shopify-payments-dispute.md)
**Retrieve all disputes ordered by initiated_at date and time (ISO 8601 format), with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202004_get_shopify_payments_disputes`

https://shopify.dev/docs/admin-api/rest/reference/shopify_payments/dispute#index-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since_id` | query | any | No | Return only disputes after the specified ID. |
| `last_id` | query | any | No | Return only disputes before the specified ID. |
| `status` | query | any | No | Return only disputes with the specified status. |
| `initiated_at` | query | any | No | Return only disputes with the specified initiated_at date (ISO 8601 format). |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

