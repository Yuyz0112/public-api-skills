# workers_binding_kind_wasm_module

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `part` | string | Yes | The name of the file containing the WebAssembly module content. Only accepted for `service worker syntax` Workers. |
| `type` | enum: wasm_module | Yes | The kind of resource that the binding provides. |

