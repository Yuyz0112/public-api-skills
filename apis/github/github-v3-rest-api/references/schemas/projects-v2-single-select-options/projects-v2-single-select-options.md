# projects-v2-single-select-options

An option for a single select field

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of the option. |
| `name` | object | Yes | The display name of the option, in raw text and HTML formats. |
| `description` | object | Yes | The description of the option, in raw text and HTML formats. |
| `color` | string | Yes | The color associated with the option. |

## Nested Fields

### `name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `raw` | string | Yes |  |
| `html` | string | Yes |  |

### `description`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `raw` | string | Yes |  |
| `html` | string | Yes |  |

