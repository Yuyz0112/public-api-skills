# workers_binding_kind_workflow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `class_name` | string | No | Class name of the Workflow. Should only be provided if the Workflow belongs to this script. |
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `script_name` | string | No | Script name that contains the Workflow. If not provided, defaults to this script name. |
| `type` | enum: workflow | Yes | The kind of resource that the binding provides. |
| `workflow_name` | string | Yes | Name of the Workflow to bind to. |

