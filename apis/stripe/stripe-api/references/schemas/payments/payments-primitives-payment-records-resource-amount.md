# payments_primitives_payment_records_resource_amount

A representation of an amount of money, consisting of an amount and a currency.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `value` | integer | Yes | A positive integer representing the amount in the currency's [minor unit](https://docs.stripe.com/currencies#zero-decimal). For example, `100` can represent 1 USD or 100 JPY. |

