# insights_resources_payment_evaluation_refunded

Refunded Event details attached to this payment evaluation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount refunded for this payment. A positive integer representing how much to charge in [the smallest currency unit](https://docs.stripe.com/currencies#zero-decimal) (for example, 100 cents to charge 1.00 USD or 100 to charge 100 Yen, a zero-decimal currency). |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `reason` | enum: duplicate, fraudulent, other... | Yes | Indicates the reason for the refund. |

