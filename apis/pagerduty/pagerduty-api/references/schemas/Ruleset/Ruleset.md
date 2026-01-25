# Ruleset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of the Ruleset. |
| `self` | string (url) | No | the API show URL at which the object is accessible |
| `type` | enum: global, default_global | No |  |
| `name` | string | No | Name of the Ruleset. |
| `routing_keys` | string[] | No | Routing keys routed to this Ruleset. |
| `created_at` | string (date-time) | No | The date the Ruleset was created at. |
| `creator` | object | No | Reference to the user that has created the Ruleset. |
| `updated_at` | string (date-time) | No | The date the Ruleset was last updated. |
| `updater` | object | No | Reference to the user that has updated the Ruleset last. |
| `team` | object | No | Reference to the team that owns the Ruleset. If none is specified, only admins have access. |

## Nested Fields

### `creator`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |

### `updater`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |

### `team`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `type` | string | Yes | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |

