# treasury.financial_account

Stripe Treasury provides users with a container for money called a FinancialAccount that is separate from their Payments balance.
FinancialAccounts serve as the source and destination of Treasury’s money movement APIs.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_features` | string[] | No | The array of paths to active Features in the Features hash. |
| `balance` | [treasury_financial_accounts_resource_balance](treasury-financial-accounts-resource-balance.md) | Yes |  |
| `country` | string | Yes | Two-letter country code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)). |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `features` | [treasury.financial_account_features](treasury-financial-account-features.md) | No |  |
| `financial_addresses` | treasury_financial_accounts_resource_financial_address[] | Yes | The set of credentials that resolve to a FinancialAccount. |
| `id` | string | Yes | Unique identifier for the object. |
| `is_default` | boolean | No |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `nickname` | string | No | The nickname for the FinancialAccount. |
| `object` | enum: treasury.financial_account | Yes | String representing the object's type. Objects of the same type share the same value. |
| `pending_features` | string[] | No | The array of paths to pending Features in the Features hash. |
| `platform_restrictions` | any | No | The set of functionalities that the platform can restrict on the FinancialAccount. |
| `restricted_features` | string[] | No | The array of paths to restricted Features in the Features hash. |
| `status` | enum: closed, open | Yes | Status of this FinancialAccount. |
| `status_details` | [treasury_financial_accounts_resource_status_details](treasury-financial-accounts-resource-status-details.md) | Yes |  |
| `supported_currencies` | string[] | Yes | The currencies the FinancialAccount can hold a balance in. Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. |

