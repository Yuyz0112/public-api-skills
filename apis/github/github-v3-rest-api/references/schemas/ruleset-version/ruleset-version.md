# ruleset-version

The historical version of a ruleset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `version_id` | integer | Yes | The ID of the previous version of the ruleset |
| `actor` | object | Yes | The actor who updated the ruleset |
| `updated_at` | string (date-time) | Yes |  |

## Nested Fields

### `actor`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `type` | string | No |  |

