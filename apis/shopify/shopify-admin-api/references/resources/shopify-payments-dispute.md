# shopify_payments/dispute

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/shopify_payments/disputes.json` | Retrieve all disputes ordered by initiated_at date and time (ISO 8601 format), with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-shopify-payments-disputes.md) |
| GET | `/admin/api/2020-01/shopify_payments/disputes/{dispute_id}.json` | Retrieves a single dispute by ID. | [View](../operations/deprecated-202001-get-shopify-payments-disputes-param-dispute-id.md) |
| GET | `/admin/api/2020-04/shopify_payments/disputes.json` | Retrieve all disputes ordered by initiated_at date and time (ISO 8601 format), with the most recent being first.
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-shopify-payments-disputes.md) |
