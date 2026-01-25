# StatusUpdateTemplateInput

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `incident_id` | string | No | The incident id to render the template for |
| `status_update` | object | No |  |
| `external` | any | No | An optional object collection that can be referenced in the template. |

## Nested Fields

### `status_update`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No | An optional status update message that will be sent to the template |

