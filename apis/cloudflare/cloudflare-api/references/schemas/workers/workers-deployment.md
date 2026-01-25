# workers_deployment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annotations` | object | No |  |
| `author_email` | string (email) | No |  |
| `created_on` | string (date-time) | Yes |  |
| `id` | string (uuid) | Yes |  |
| `source` | string | Yes |  |
| `strategy` | enum: percentage | Yes |  |
| `versions` | object[] | Yes |  |

## Nested Fields

### `annotations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `workers/message` | string | No | Human-readable message about the deployment. Truncated to 100 bytes. |
| `workers/triggered_by` | string | No | Operation that triggered the creation of the deployment. |

### `versions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `percentage` | number | Yes |  |
| `version_id` | string (uuid) | Yes |  |

