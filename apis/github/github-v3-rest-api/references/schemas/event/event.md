# event

Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `type` | string | Yes |  |
| `actor` | [actor](actor.md) | Yes |  |
| `repo` | object | Yes |  |
| `org` | [actor](actor.md) | No |  |
| `payload` | any | Yes |  |
| `public` | boolean | Yes |  |
| `created_at` | string (date-time) | Yes |  |

## Nested Fields

### `repo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `name` | string | Yes |  |
| `url` | string (uri) | Yes |  |

