# checkout_acss_debit_mandate_options

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `custom_mandate_url` | string | No | A URL for custom mandate text |
| `default_for` | string[] | No | List of Stripe products where this mandate can be selected automatically. Returned when the Session is in `setup` mode. |
| `interval_description` | string | No | Description of the interval. Only required if the 'payment_schedule' parameter is 'interval' or 'combined'. |
| `payment_schedule` | enum: combined, interval, sporadic | No | Payment schedule for the mandate. |
| `transaction_type` | enum: business, personal | No | Transaction type of the mandate. |

