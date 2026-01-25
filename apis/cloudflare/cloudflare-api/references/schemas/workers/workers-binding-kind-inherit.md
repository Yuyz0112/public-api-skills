# workers_binding_kind_inherit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the inherited binding. |
| `old_name` | string | No | The old name of the inherited binding. If set, the binding will be renamed from `old_name` to `name` in the new version. If not set, the binding will keep the same name between versions. |
| `type` | enum: inherit | Yes | The kind of resource that the binding provides. |
| `version_id` | string | No | Identifier for the version to inherit the binding from, which can be the version ID or the literal "latest" to inherit from the latest version. Defaults to inheriting the binding from the latest version. |

