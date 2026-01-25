# workers-observability_query_results

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `calculations` | object[] | No |  |
| `compare` | object[] | No |  |
| `events` | object | No |  |
| `invocations` | object | No |  |
| `patterns` | object[] | No |  |
| `run` | [workers-observability_query_run](workers-observability-query-run.md) | Yes |  |
| `statistics` | [workers-observability_performance_information](workers-observability-performance-information.md) | Yes |  |
| `traces` | object[] | No |  |

## Nested Fields

### `calculations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aggregates` | object[] | Yes |  |
| `alias` | string | No |  |
| `calculation` | string | Yes |  |
| `series` | object[] | Yes |  |

#### `calculations.aggregates`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | Yes |  |
| `groups` | object[] | No |  |
| `interval` | number | Yes |  |
| `sampleInterval` | number | Yes |  |
| `value` | number | Yes |  |

#### `calculations.series`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object[] | Yes |  |
| `time` | string | Yes |  |

### `compare`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aggregates` | object[] | Yes |  |
| `alias` | string | No |  |
| `calculation` | string | Yes |  |
| `series` | object[] | Yes |  |

#### `compare.aggregates`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | Yes |  |
| `groups` | object[] | No |  |
| `interval` | number | Yes |  |
| `sampleInterval` | number | Yes |  |
| `value` | number | Yes |  |

#### `compare.series`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object[] | Yes |  |
| `time` | string | Yes |  |

### `events`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | No |  |
| `events` | workers-observability_telemetry_event[] | No |  |
| `fields` | object[] | No |  |
| `series` | object[] | No |  |

#### `events.fields`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes |  |
| `type` | string | Yes |  |

#### `events.series`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object[] | Yes |  |
| `time` | string | Yes |  |

### `patterns`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | Yes |  |
| `pattern` | string | Yes |  |
| `series` | object[] | Yes |  |
| `service` | string | Yes |  |

#### `patterns.series`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | Yes |  |
| `time` | string | Yes |  |

### `traces`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | string[] | No |  |
| `rootSpanName` | string | Yes |  |
| `rootTransactionName` | string | Yes |  |
| `service` | string[] | Yes |  |
| `spans` | number | Yes |  |
| `traceDurationMs` | number | Yes |  |
| `traceEndMs` | number | Yes |  |
| `traceId` | string | Yes |  |
| `traceStartMs` | number | Yes |  |

