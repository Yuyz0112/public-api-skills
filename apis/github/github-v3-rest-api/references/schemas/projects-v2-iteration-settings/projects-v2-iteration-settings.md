# projects-v2-iteration-settings

An iteration setting for an iteration field

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of the iteration setting. |
| `start_date` | string (date) | Yes | The start date of the iteration. |
| `duration` | integer | Yes | The duration of the iteration in days. |
| `title` | object | Yes | The iteration title, in raw text and HTML formats. |
| `completed` | boolean | Yes | Whether the iteration has been completed. |

## Nested Fields

### `title`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `raw` | string | Yes |  |
| `html` | string | Yes |  |

