# workers-observability_telemetry_event

The data structure of a telemetry event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `$containers` | object | No | Cloudflare Containers event information enriches your logs so you can easily identify and debug issues. |
| `$metadata` | object | Yes |  |
| `$workers` | any | No | Cloudflare Workers event information enriches your logs so you can easily identify and debug issues. |
| `dataset` | string | Yes |  |
| `source` | any | Yes |  |
| `timestamp` | integer | Yes |  |

## Nested Fields

### `$metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | string | No |  |
| `cloudService` | string | No |  |
| `coldStart` | integer | No |  |
| `cost` | integer | No |  |
| `duration` | integer | No |  |
| `endTime` | integer | No |  |
| `error` | string | No |  |
| `errorTemplate` | string | No |  |
| `fingerprint` | string | No |  |
| `id` | string | Yes |  |
| `level` | string | No |  |
| `message` | string | No |  |
| `messageTemplate` | string | No |  |
| `metricName` | string | No |  |
| `origin` | string | No |  |
| `parentSpanId` | string | No |  |
| `provider` | string | No |  |
| `region` | string | No |  |
| `requestId` | string | No |  |
| `service` | string | No |  |
| `spanId` | string | No |  |
| `spanName` | string | No |  |
| `stackId` | string | No |  |
| `startTime` | integer | No |  |
| `statusCode` | integer | No |  |
| `traceDuration` | integer | No |  |
| `traceId` | string | No |  |
| `transactionName` | string | No |  |
| `trigger` | string | No |  |
| `type` | string | No |  |
| `url` | string | No |  |

