# cash_balance

A customer's `Cash balance` represents real funds. Customers can add funds to their cash balance by sending a bank transfer. These funds can be used for payment and can eventually be paid out to your bank account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `available` | object | No | A hash of all cash balances available to this customer. You cannot delete a customer with any cash balances, even if the balance is 0. Amounts are represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `customer` | string | Yes | The ID of the customer whose cash balance this object represents. |
| `customer_account` | string | No | The ID of an Account representing a customer whose cash balance this object represents. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: cash_balance | Yes | String representing the object's type. Objects of the same type share the same value. |
| `settings` | [customer_balance_customer_balance_settings](customer-balance-customer-balance-settings.md) | Yes |  |

