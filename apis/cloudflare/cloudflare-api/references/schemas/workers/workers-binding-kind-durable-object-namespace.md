# workers_binding_kind_durable_object_namespace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `class_name` | string | No | The exported class name of the Durable Object. |
| `environment` | string | No | The environment of the script_name to bind to. |
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `namespace_id` | any | No |  |
| `script_name` | string | No | The script where the Durable Object is defined, if it is external to this Worker. |
| `type` | enum: durable_object_namespace | Yes | The kind of resource that the binding provides. |

