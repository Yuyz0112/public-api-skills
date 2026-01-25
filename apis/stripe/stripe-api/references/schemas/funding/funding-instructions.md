# funding_instructions

Each customer has a [`balance`](https://docs.stripe.com/api/customers/object#customer_object-balance) that is
automatically applied to future invoices and payments using the `customer_balance` payment method.
Customers can fund this balance by initiating a bank transfer to any account in the
`financial_addresses` field.
Related guide: [Customer balance funding instructions](https://docs.stripe.com/payments/customer-balance/funding-instructions)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank_transfer` | [funding_instructions_bank_transfer](funding-instructions-bank-transfer.md) | Yes |  |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `funding_type` | enum: bank_transfer | Yes | The `funding_type` of the returned instructions |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: funding_instructions | Yes | String representing the object's type. Objects of the same type share the same value. |

