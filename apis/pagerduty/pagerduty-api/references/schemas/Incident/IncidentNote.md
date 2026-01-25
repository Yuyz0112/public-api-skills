# IncidentNote

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `user` | any | No |  |
| `channel` | object | No | The means by which this Note was created. Has different formats depending on type. |
| `content` | string | Yes | The note content |
| `created_at` | string (date-time) | No | The time at which the note was submitted |
| `updated_at` | string (date-time) | No | The time at which the note was last updated |

## Nested Fields

### `channel`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `summary` | string | Yes | A string describing the source of the Note. |
| `id` | string | No |  |
| `type` | string | No | A string that determines the schema of the object |
| `self` | string (url) | No | The API show URL at which the object is accessible |
| `html_url` | string (url) | No | a URL at which the entity is uniquely displayed in the Web app |

