# workers_binding_kind_text_blob

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `part` | string | Yes | The name of the file containing the text content. Only accepted for `service worker syntax` Workers. |
| `type` | enum: text_blob | Yes | The kind of resource that the binding provides. |

