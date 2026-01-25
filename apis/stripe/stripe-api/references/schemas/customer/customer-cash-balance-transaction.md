# customer_cash_balance_transaction

Customers with certain payments enabled have a cash balance, representing funds that were paid
by the customer to a merchant, but have not yet been allocated to a payment. Cash Balance Transactions
represent when funds are moved into or out of this balance. This includes funding by the customer, allocation
to payments, and refunds to the customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `adjusted_for_overdraft` | [customer_balance_resource_cash_balance_transaction_resource_adjusted_for_overdraft](customer-balance-resource-cash-balance-transaction-resource-adjusted-for-overdraft.md) | No |  |
| `applied_to_payment` | [customer_balance_resource_cash_balance_transaction_resource_applied_to_payment_transaction](customer-balance-resource-cash-balance-transaction-resource-applied-to-payment-transaction.md) | No |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | any | Yes | The customer whose available cash balance changed as a result of this transaction. |
| `customer_account` | string | No | The ID of an Account representing a customer whose available cash balance changed as a result of this transaction. |
| `ending_balance` | integer | Yes | The total available cash balance for the specified currency after this transaction was applied. Represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `funded` | [customer_balance_resource_cash_balance_transaction_resource_funded_transaction](customer-balance-resource-cash-balance-transaction-resource-funded-transaction.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `net_amount` | integer | Yes | The amount by which the cash balance changed, represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). A positive value represents funds being added to the cash balance, a negative value represents funds being removed from the cash balance. |
| `object` | enum: customer_cash_balance_transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `refunded_from_payment` | [customer_balance_resource_cash_balance_transaction_resource_refunded_from_payment_transaction](customer-balance-resource-cash-balance-transaction-resource-refunded-from-payment-transaction.md) | No |  |
| `transferred_to_balance` | [customer_balance_resource_cash_balance_transaction_resource_transferred_to_balance](customer-balance-resource-cash-balance-transaction-resource-transferred-to-balance.md) | No |  |
| `type` | enum: adjusted_for_overdraft, applied_to_payment, funded... | Yes | The type of the cash balance transaction. New types may be added in future. See [Customer Balance](https://docs.stripe.com/payments/customer-balance#types) to learn more about these types. |
| `unapplied_from_payment` | [customer_balance_resource_cash_balance_transaction_resource_unapplied_from_payment_transaction](customer-balance-resource-cash-balance-transaction-resource-unapplied-from-payment-transaction.md) | No |  |

