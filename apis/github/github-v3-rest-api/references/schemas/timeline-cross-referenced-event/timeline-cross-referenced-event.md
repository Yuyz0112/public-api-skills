# timeline-cross-referenced-event

Timeline Cross Referenced Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event` | string | Yes |  |
| `actor` | [simple-user](simple-user.md) | No |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `source` | object | Yes |  |

## Nested Fields

### `source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No |  |
| `issue` | [issue](issue.md) | No |  |

