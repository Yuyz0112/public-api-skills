# projects-v2-field-iteration-configuration

The configuration for iteration fields.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `start_date` | string (date) | No | The start date of the first iteration. |
| `duration` | integer | No | The default duration for iterations in days. Individual iterations can override this value. |
| `iterations` | object[] | No | Zero or more iterations for the field. |

## Nested Fields

### `iterations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `title` | string | No | The title of the iteration. |
| `start_date` | string (date) | No | The start date of the iteration. |
| `duration` | integer | No | The duration of the iteration in days. |

