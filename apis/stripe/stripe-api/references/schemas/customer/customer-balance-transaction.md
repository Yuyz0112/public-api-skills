# customer_balance_transaction

Each customer has a [Balance](https://docs.stripe.com/api/customers/object#customer_object-balance) value,
which denotes a debit or credit that's automatically applied to their next invoice upon finalization.
You may modify the value directly by using the [update customer API](https://docs.stripe.com/api/customers/update),
or by creating a Customer Balance Transaction, which increments or decrements the customer's `balance` by the specified `amount`.

Related guide: [Customer balance](https://docs.stripe.com/billing/customer/balance)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount of the transaction. A negative value is a credit for the customer's balance, and a positive value is a debit to the customer's `balance`. |
| `checkout_session` | any | No | The ID of the checkout session (if any) that created the transaction. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `credit_note` | any | No | The ID of the credit note (if any) related to the transaction. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | any | Yes | The ID of the customer the transaction belongs to. |
| `customer_account` | string | No | The ID of an Account representing a customer that the transaction belongs to. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `ending_balance` | integer | Yes | The customer's `balance` after the transaction was applied. A negative value decreases the amount due on the customer's next invoice. A positive value increases the amount due on the customer's next invoice. |
| `id` | string | Yes | Unique identifier for the object. |
| `invoice` | any | No | The ID of the invoice (if any) related to the transaction. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: customer_balance_transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `type` | enum: adjustment, applied_to_invoice, checkout_session_subscription_payment... | Yes | Transaction type: `adjustment`, `applied_to_invoice`, `credit_note`, `initial`, `invoice_overpaid`, `invoice_too_large`, `invoice_too_small`, `unspent_receiver_credit`, `unapplied_from_invoice`, `checkout_session_subscription_payment`, or `checkout_session_subscription_payment_canceled`. See the [Customer Balance page](https://docs.stripe.com/billing/customer/balance#types) to learn more about transaction types. |

