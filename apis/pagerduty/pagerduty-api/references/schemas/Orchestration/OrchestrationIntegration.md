# OrchestrationIntegration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of the Integration. |
| `label` | string | No | Name of the Integration. |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `routing_key` | string | No | Routing Key used to send Events to this Orchestration |
| `type` | string | No |  |

