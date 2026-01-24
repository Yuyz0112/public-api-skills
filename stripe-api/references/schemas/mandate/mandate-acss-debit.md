# mandate_acss_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default_for` | string[] | No | List of Stripe products where this mandate can be selected automatically. |
| `interval_description` | string | No | Description of the interval. Only required if the 'payment_schedule' parameter is 'interval' or 'combined'. |
| `payment_schedule` | enum: combined, interval, sporadic | Yes | Payment schedule for the mandate. |
| `transaction_type` | enum: business, personal | Yes | Transaction type of the mandate. |

