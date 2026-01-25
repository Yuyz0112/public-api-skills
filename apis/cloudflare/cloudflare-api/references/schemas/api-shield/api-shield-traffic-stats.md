# api-shield_traffic_stats

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `traffic_stats` | object | No |  |

## Nested Fields

### `traffic_stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `last_updated` | [api-shield_schemas-timestamp](api-shield-schemas-timestamp.md) | Yes |  |
| `period_seconds` | integer | Yes | The period in seconds these statistics were computed over |
| `requests` | number (float) | Yes | The average number of requests seen during this period |

