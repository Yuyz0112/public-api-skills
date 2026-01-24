# balance_amount_by_source_type

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank_account` | integer | No | Amount coming from [legacy US ACH payments](https://docs.stripe.com/ach-deprecated). |
| `card` | integer | No | Amount coming from most payment methods, including cards as well as [non-legacy bank debits](https://docs.stripe.com/payments/bank-debits). |
| `fpx` | integer | No | Amount coming from [FPX](https://docs.stripe.com/payments/fpx), a Malaysian payment method. |

