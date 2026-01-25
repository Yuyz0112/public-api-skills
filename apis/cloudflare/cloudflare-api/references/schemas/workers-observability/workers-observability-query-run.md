# workers-observability_query_run

A Workers Observability Query Object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountId` | string | Yes |  |
| `created` | string | No |  |
| `dry` | boolean | Yes |  |
| `environmentId` | string | Yes |  |
| `granularity` | number | Yes |  |
| `id` | string | Yes |  |
| `query` | [workers-observability_query](workers-observability-query.md) | Yes |  |
| `statistics` | object | No |  |
| `status` | enum: STARTED, COMPLETED | Yes |  |
| `timeframe` | object | Yes | Time range for the query execution |
| `updated` | string | No |  |
| `userId` | string | Yes |  |
| `workspaceId` | string | Yes |  |

## Nested Fields

### `statistics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `abr_level` | number | No | The level of Adaptive Bit Rate (ABR) sampling used for the query. If empty the ABR level is 1 |
| `bytes_read` | number | Yes | Number of uncompressed bytes read from the table. |
| `elapsed` | number | Yes | Time in seconds for the query to run. |
| `rows_read` | number | Yes | Number of rows scanned from the table. |

### `timeframe`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | number | Yes | Start timestamp for the query timeframe (Unix timestamp in milliseconds) |
| `to` | number | Yes | End timestamp for the query timeframe (Unix timestamp in milliseconds) |

