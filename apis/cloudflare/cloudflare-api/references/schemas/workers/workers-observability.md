# workers_observability

Observability settings for the Worker.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Whether observability is enabled for the Worker. |
| `head_sampling_rate` | number | No | The sampling rate for incoming requests. From 0 to 1 (1 = 100%, 0.1 = 10%). Default is 1. |
| `logs` | object | No | Log settings for the Worker. |

## Nested Fields

### `logs`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destinations` | string[] | No | A list of destinations where logs will be exported to. |
| `enabled` | boolean | Yes | Whether logs are enabled for the Worker. |
| `head_sampling_rate` | number | No | The sampling rate for logs. From 0 to 1 (1 = 100%, 0.1 = 10%). Default is 1. |
| `invocation_logs` | boolean | Yes | Whether [invocation logs](https://developers.cloudflare.com/workers/observability/logs/workers-logs/#invocation-logs) are enabled for the Worker. |
| `persist` | boolean | No | Whether log persistence is enabled for the Worker. |

