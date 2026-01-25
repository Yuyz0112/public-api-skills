# financial_connections.account

A Financial Connections Account represents an account that exists outside of Stripe, to which you have been granted some degree of access.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder` | any | No | The account holder that this account belongs to. |
| `account_numbers` | bank_connections_resource_account_number_details[] | No | Details about the account numbers. |
| `balance` | any | No | The most recent information about the account's balance. |
| `balance_refresh` | any | No | The state of the most recent attempt to refresh the account balance. |
| `category` | enum: cash, credit, investment... | Yes | The type of the account. Account category is further divided in `subcategory`. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `display_name` | string | No | A human-readable name that has been assigned to this account, either by the account holder or by the institution. |
| `id` | string | Yes | Unique identifier for the object. |
| `institution_name` | string | Yes | The name of the institution that holds this account. |
| `last4` | string | No | The last 4 digits of the account number. If present, this will be 4 numeric characters. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: financial_connections.account | Yes | String representing the object's type. Objects of the same type share the same value. |
| `ownership` | any | No | The most recent information about the account's owners. |
| `ownership_refresh` | any | No | The state of the most recent attempt to refresh the account owners. |
| `permissions` | string[] | No | The list of permissions granted by this account. |
| `status` | enum: active, disconnected, inactive | Yes | The status of the link to the account. |
| `subcategory` | enum: checking, credit_card, line_of_credit... | Yes | If `category` is `cash`, one of:

 - `checking`
 - `savings`
 - `other`

If `category` is `credit`, one of:

 - `mortgage`
 - `line_of_credit`
 - `credit_card`
 - `other`

If `category` is `investment` or `other`, this will be `other`. |
| `subscriptions` | string[] | No | The list of data refresh subscriptions requested on this account. |
| `supported_payment_method_types` | string[] | Yes | The [PaymentMethod type](https://docs.stripe.com/api/payment_methods/object#payment_method_object-type)(s) that can be created from this account. |
| `transaction_refresh` | any | No | The state of the most recent attempt to refresh the account transactions. |

