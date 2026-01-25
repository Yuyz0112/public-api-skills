# billing.credit_balance_transaction

A credit balance transaction is a resource representing a transaction (either a credit or a debit) against an existing credit grant.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `credit` | any | No | Credit details for this credit balance transaction. Only present if type is `credit`. |
| `credit_grant` | any | Yes | The credit grant associated with this credit balance transaction. |
| `debit` | any | No | Debit details for this credit balance transaction. Only present if type is `debit`. |
| `effective_at` | integer (unix-time) | Yes | The effective time of this credit balance transaction. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: billing.credit_balance_transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `test_clock` | any | No | ID of the test clock this credit balance transaction belongs to. |
| `type` | enum: credit, debit | No | The type of credit balance transaction (credit or debit). |

