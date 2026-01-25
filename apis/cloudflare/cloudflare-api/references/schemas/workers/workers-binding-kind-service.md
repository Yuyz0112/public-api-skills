# workers_binding_kind_service

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environment` | string | No | Optional environment if the Worker utilizes one. |
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `service` | string | Yes | Name of Worker to bind to. |
| `type` | enum: service | Yes | The kind of resource that the binding provides. |

