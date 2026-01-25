# aaa_audit-logs

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | object | No |  |
| `actor` | object | No |  |
| `id` | string | No | A string that uniquely identifies the audit log. |
| `interface` | string | No | The source of the event. |
| `metadata` | object | No | An object which can lend more context to the action being logged. This is a flexible value and varies between different actions. |
| `newValue` | string | No | The new value of the resource that was modified. |
| `oldValue` | string | No | The value of the resource before it was modified. |
| `owner` | object | No |  |
| `resource` | object | No |  |
| `when` | string (date-time) | No | A UTC RFC3339 timestamp that specifies when the action being logged occured. |

## Nested Fields

### `action`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `result` | boolean | No | A boolean that indicates if the action attempted was successful. |
| `type` | string | No | A short string that describes the action that was performed. |

### `actor`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string (email) | No | The email of the user that performed the action. |
| `id` | string | No | The ID of the actor that performed the action. If a user performed the action, this will be their User ID. |
| `ip` | string | No | The IP address of the request that performed the action. |
| `type` | enum: user, admin, Cloudflare | No | The type of actor, whether a User, Cloudflare Admin, or an Automated System. |

### `owner`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [aaa_identifier](aaa-identifier.md) | No |  |

### `resource`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | An identifier for the resource that was affected by the action. |
| `type` | string | No | A short string that describes the resource that was affected by the action. |

