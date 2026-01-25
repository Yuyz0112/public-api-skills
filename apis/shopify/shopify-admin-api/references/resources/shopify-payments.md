# shopify_payments

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/deprecated-202001-get-shopify-payments-balance.md) |
| GET | `/admin/api/2020-04/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/deprecated-202004-get-shopify-payments-balance.md) |
| GET | `/admin/api/2020-07/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/deprecated-202007-get-shopify-payments-balance.md) |
| GET | `/admin/api/2020-10/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/get-shopify-payments-balance.md) |
| GET | `/admin/api/2021-01/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/deprecated-202101-get-shopify-payments-balance.md) |
| GET | `/admin/api/unstable/shopify_payments/balance.json` | Retrieves the account's current balance. | [View](../operations/deprecated-unstable-get-shopify-payments-balance.md) |
| GET | `/admin/api/2020-01/shopify_payments/disputes.json` | Retrieve all disputes ordered by initiated_at date and time (ISO 8601 format), with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-shopify-payments-disputes.md) |
| GET | `/admin/api/2020-01/shopify_payments/disputes/{dispute_id}.json` | Retrieves a single dispute by ID. | [View](../operations/deprecated-202001-get-shopify-payments-disputes-param-dispute-id.md) |
| GET | `/admin/api/2020-04/shopify_payments/disputes.json` | Retrieve all disputes ordered by initiated_at date and time (ISO 8601 format), with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-shopify-payments-disputes.md) |
| GET | `/admin/api/2020-01/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-shopify-payments-payouts.md) |
| GET | `/admin/api/2020-01/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/deprecated-202001-get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/2020-04/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-shopify-payments-payouts.md) |
| GET | `/admin/api/2020-04/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/deprecated-202004-get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/2020-07/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-shopify-payments-payouts.md) |
| GET | `/admin/api/2020-07/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/deprecated-202007-get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/2020-10/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-shopify-payments-payouts.md) |
| GET | `/admin/api/2020-10/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/2021-01/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-shopify-payments-payouts.md) |
| GET | `/admin/api/2021-01/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/deprecated-202101-get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/unstable/shopify_payments/payouts.json` | Retrieves a list of all payouts ordered by payout date, with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-shopify-payments-payouts.md) |
| GET | `/admin/api/unstable/shopify_payments/payouts/{payout_id}.json` | Retrieves a single payout by id. | [View](../operations/deprecated-unstable-get-shopify-payments-payouts-param-payout-id.md) |
| GET | `/admin/api/2020-01/shopify_payments/balance/transactions.json` | Retrieves a list of all balance transactions ordered by processing
time, with the most recent being first.
Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-shopify-payments-balance-transactions.md) |
