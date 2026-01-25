# payment_method_details_affirm

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `location` | string | No | ID of the [location](https://docs.stripe.com/api/terminal/locations) that this transaction's reader is assigned to. |
| `reader` | string | No | ID of the [reader](https://docs.stripe.com/api/terminal/readers) this transaction was made on. |
| `transaction_id` | string | No | The Affirm transaction ID associated with this payment. |

