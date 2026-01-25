# runner-label

A label for a self hosted runner

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | Unique identifier of the label. |
| `name` | string | Yes | Name of the label. |
| `type` | enum: read-only, custom | No | The type of label. Read-only labels are applied automatically when the runner is configured. |

