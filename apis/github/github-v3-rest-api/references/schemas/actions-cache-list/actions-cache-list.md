# actions-cache-list

Repository actions caches

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_count` | integer | Yes | Total number of caches |
| `actions_caches` | object[] | Yes | Array of caches |

## Nested Fields

### `actions_caches`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `ref` | string | No |  |
| `key` | string | No |  |
| `version` | string | No |  |
| `last_accessed_at` | string (date-time) | No |  |
| `created_at` | string (date-time) | No |  |
| `size_in_bytes` | integer | No |  |

