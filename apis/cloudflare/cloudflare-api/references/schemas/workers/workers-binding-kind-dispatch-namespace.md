# workers_binding_kind_dispatch_namespace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `namespace` | string | Yes | The name of the dispatch namespace. |
| `outbound` | object | No | Outbound worker. |
| `type` | enum: dispatch_namespace | Yes | The kind of resource that the binding provides. |

## Nested Fields

### `outbound`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `params` | string[] | No | Pass information from the Dispatch Worker to the Outbound Worker through the parameters. |
| `worker` | object | No | Outbound worker. |

#### `outbound.worker`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environment` | string | No | Environment of the outbound worker. |
| `service` | string | No | Name of the outbound worker. |

