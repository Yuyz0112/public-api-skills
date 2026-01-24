# setup_intent_payment_method_options_mandate_options_acss_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `custom_mandate_url` | string | No | A URL for custom mandate text |
| `default_for` | string[] | No | List of Stripe products where this mandate can be selected automatically. |
| `interval_description` | string | No | Description of the interval. Only required if the 'payment_schedule' parameter is 'interval' or 'combined'. |
| `payment_schedule` | enum: combined, interval, sporadic | No | Payment schedule for the mandate. |
| `transaction_type` | enum: business, personal | No | Transaction type of the mandate. |

