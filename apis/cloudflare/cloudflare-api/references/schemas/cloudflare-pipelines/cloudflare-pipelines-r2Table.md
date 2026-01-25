# cloudflare-pipelines_r2Table

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | string | Yes | Cloudflare Account ID for the bucket |
| `bucket` | string | Yes | R2 Bucket to write to |
| `credentials` | object | Yes |  |
| `file_naming` | object | No | Controls filename prefix/suffix and strategy. |
| `jurisdiction` | string | No | Jurisdiction this bucket is hosted in |
| `partitioning` | object | No | Data-layout partitioning for sinks. |
| `path` | string | No | Subpath within the bucket to write to |
| `rolling_policy` | object | No | Rolling policy for file sinks (when & why to close a file and open a new one). |

## Nested Fields

### `credentials`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_key_id` | string (var-str) | Yes | Cloudflare Account ID for the bucket |
| `secret_access_key` | string (var-str) | Yes | Cloudflare Account ID for the bucket |

### `file_naming`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `prefix` | string | No | The prefix to use in file name. i.e prefix-<uuid>.parquet |
| `strategy` | enum: serial, uuid, uuid_v7... | No | Filename generation strategy. |
| `suffix` | string | No | This will overwrite the default file suffix. i.e .parquet, use with caution |

### `partitioning`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `time_pattern` | string | No | The pattern of the date string |

### `rolling_policy`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file_size_bytes` | integer (uint64) | No | Files will be rolled after reaching this number of bytes |
| `inactivity_seconds` | integer (uint64) | No | Number of seconds of inactivity to wait before rolling over to a new file |
| `interval_seconds` | integer (uint64) | No | Number of seconds to wait before rolling over to a new file |

