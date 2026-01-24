# financial_connections.account_owner

Describes an owner of an account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string | No | The email address of the owner. |
| `id` | string | Yes | Unique identifier for the object. |
| `name` | string | Yes | The full name of the owner. |
| `object` | enum: financial_connections.account_owner | Yes | String representing the object's type. Objects of the same type share the same value. |
| `ownership` | string | Yes | The ownership object that this owner belongs to. |
| `phone` | string | No | The raw phone number of the owner. |
| `raw_address` | string | No | The raw physical address of the owner. |
| `refreshed_at` | integer (unix-time) | No | The timestamp of the refresh that updated this owner. |

