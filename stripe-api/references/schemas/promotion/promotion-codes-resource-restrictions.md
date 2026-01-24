# promotion_codes_resource_restrictions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currency_options` | object | No | Promotion code restrictions defined in each available currency option. Each key must be a three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html) and a [supported currency](https://stripe.com/docs/currencies). |
| `first_time_transaction` | boolean | Yes | A Boolean indicating if the Promotion Code should only be redeemed for Customers without any successful payments or invoices |
| `minimum_amount` | integer | No | Minimum amount required to redeem this Promotion Code into a Coupon (e.g., a purchase must be $100 or more to work). |
| `minimum_amount_currency` | string | No | Three-letter [ISO code](https://stripe.com/docs/currencies) for minimum_amount |

