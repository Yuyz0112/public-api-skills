# IncidentType

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | State of this Incident Type object. |
| `id` | string | No |  |
| `name` | string | No | The name of the Incident Type. |
| `parent` | object | No | The parent Incident Type (id/name). If omitted, type is created under top level (incident_default) |
| `type` | string | No | A string that determines the schema of the object. This must be the standard name for the entity, suffixed by `_reference` if the object is a reference. |
| `description` | string | No | A succinct description of the Incident Type. |
| `created_at` | string (date-time) | No | The time the Incident Type was created. |
| `updated_at` | string (date-time) | No | The time the Incident Type was last modified. |
| `display_name` | string | No | The display name of the Incident Type. The first character must be alphanumeric. Max length: 50, Min Length : 1. The `display_name` for a Field must be unique. |

## Nested Fields

### `parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No |  |

