# Orchestration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of the Orchestration. |
| `self` | string (url) | No | The API show URL at which the object is accessible |
| `name` | string | No | Name of the Orchestration. |
| `description` | string | No | A description of this Orchestration's purpose. |
| `team` | object | No | Reference to the team that owns the Orchestration. If none is specified, only admins have access. |
| `integrations` | OrchestrationIntegration[] | No |  |
| `routes` | integer | No | Number of different Service Orchestration being routed to |
| `created_at` | string (date-time) | No | The date the Orchestration was created at. |
| `created_by` | object | No | Reference to the user that has created the Orchestration. |
| `updated_at` | string (date-time) | No | The date the Orchestration was last updated. |
| `updated_by` | object | No | Reference to the user that has updated the Orchestration last. |
| `version` | string | No | Version of the Orchestration. |

## Nested Fields

### `team`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |

### `created_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |

### `updated_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |

