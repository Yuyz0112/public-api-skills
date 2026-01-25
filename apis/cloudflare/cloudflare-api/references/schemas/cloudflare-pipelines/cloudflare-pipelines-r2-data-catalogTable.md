# cloudflare-pipelines_r2_data_catalogTable

R2 Data Catalog Sink

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | string (uri) | Yes | Cloudflare Account ID |
| `bucket` | string | Yes | The R2 Bucket that hosts this catalog |
| `namespace` | string | No | Table namespace |
| `rolling_policy` | object | No | Rolling policy for file sinks (when & why to close a file and open a new one). |
| `table_name` | string | Yes | Table name |
| `token` | string (var-str) | Yes | Authentication token |

## Nested Fields

### `rolling_policy`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file_size_bytes` | integer (uint64) | No | Files will be rolled after reaching this number of bytes |
| `inactivity_seconds` | integer (uint64) | No | Number of seconds of inactivity to wait before rolling over to a new file |
| `interval_seconds` | integer (uint64) | No | Number of seconds to wait before rolling over to a new file |

