# GET /admin/api/2020-04/shopify_payments/payouts.json

**Resource:** [shopify_payments/payout](../resources/shopify-payments-payout.md)
**Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202004_get_shopify_payments_payouts`

https://shopify.dev/docs/admin-api/rest/reference/shopify_payments/payout#index-2020-04

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since_id` | query | any | No | Filter the response to payouts made after the specified ID. |
| `last_id` | query | any | No | Filter the response to payouts made before the specified ID. |
| `date_min` | query | any | No | Filter the response to payouts made inclusively after the specified date. |
| `date_max` | query | any | No | Filter the response to payouts made inclusively before the specified date. |
| `date` | query | any | No | Filter the response to payouts made on the specified date. |
| `status` | query | any | No | Filter the response to payouts made with the specified status. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

