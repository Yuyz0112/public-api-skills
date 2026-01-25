# r2_rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | r2_r2-action[] | Yes | Array of R2 object actions that will trigger notifications. |
| `description` | string | No | A description that can be used to identify the event notification rule after creation. |
| `prefix` | string | No | Notifications will be sent only for objects with this prefix. |
| `suffix` | string | No | Notifications will be sent only for objects with this suffix. |

