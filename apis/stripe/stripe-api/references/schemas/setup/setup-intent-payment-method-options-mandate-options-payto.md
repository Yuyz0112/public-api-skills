# setup_intent_payment_method_options_mandate_options_payto

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | Amount that will be collected. It is required when `amount_type` is `fixed`. |
| `amount_type` | enum: fixed, maximum | No | The type of amount that will be collected. The amount charged must be exact or up to the value of `amount` param for `fixed` or `maximum` type respectively. Defaults to `maximum`. |
| `end_date` | string | No | Date, in YYYY-MM-DD format, after which payments will not be collected. Defaults to no end date. |
| `payment_schedule` | enum: adhoc, annual, daily... | No | The periodicity at which payments will be collected. Defaults to `adhoc`. |
| `payments_per_period` | integer | No | The number of payments that will be made during a payment period. Defaults to 1 except for when `payment_schedule` is `adhoc`. In that case, it defaults to no limit. |
| `purpose` | enum: dependant_support, government, loan... | No | The purpose for which payments are made. Has a default value based on your merchant category code. |
| `start_date` | string | No | Date, in YYYY-MM-DD format, from which payments will be collected. Defaults to confirmation time. |

