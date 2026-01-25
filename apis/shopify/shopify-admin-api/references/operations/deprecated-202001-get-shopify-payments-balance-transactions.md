# GET /admin/api/2020-01/shopify_payments/balance/transactions.json

**Resource:** [shopify_payments/transaction](../resources/shopify-payments-transaction.md)
**Retrieves a list of all balance transactions ordered by processing
time, with the most recent being first.
Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_shopify_payments_balance_transactions`

https://shopify.dev/docs/admin-api/rest/reference/shopify_payments/transaction#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since_id` | query | any | No | Filter response to transactions exclusively after the specified ID. |
| `last_id` | query | any | No | Filter response to transactions exclusively before the specified ID |
| `test` | query | any | No | Filter response to transactions placed in test mode. |
| `payout_id` | query | any | No | Filter response to transactions paid out in the specified payout. |
| `payout_status` | query | any | No | Filter response to transactions with the specified payout status |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

