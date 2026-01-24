# financial_connections.account_ownership

Describes a snapshot of the owners of an account at a particular point in time.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `object` | enum: financial_connections.account_ownership | Yes | String representing the object's type. Objects of the same type share the same value. |
| `owners` | object | Yes | A paginated list of owners for this account. |

## Nested Fields

### `owners`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | financial_connections.account_owner[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

