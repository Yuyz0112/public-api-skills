# cloudflare-pipelines_workers-pipelines-pipeline

[DEPRECATED] Describes the configuration of a pipeline. Use the new streams/sinks/pipelines API instead.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destination` | object | Yes |  |
| `endpoint` | string | Yes | Indicates the endpoint URL to send traffic. |
| `id` | string | Yes | Specifies the pipeline identifier. |
| `name` | string | Yes | Defines the name of the pipeline. |
| `source` | any[] | Yes |  |
| `version` | number | Yes | Indicates the version number of last saved configuration. |

## Nested Fields

### `destination`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `batch` | object | Yes |  |
| `compression` | object | Yes |  |
| `format` | enum: json | Yes | Specifies the format of data to deliver. |
| `path` | object | Yes |  |
| `type` | enum: r2 | Yes | Specifies the type of destination. |

#### `destination.batch`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_bytes` | integer | Yes | Specifies rough maximum size of files. |
| `max_duration_s` | number | Yes | Specifies duration to wait to aggregate batches files. |
| `max_rows` | integer | Yes | Specifies rough maximum number of rows per file. |

#### `destination.compression`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: none, gzip, deflate | Yes | Specifies the desired compression algorithm and format. |

#### `destination.path`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | Yes | Specifies the R2 Bucket to store files. |
| `filename` | any | No | Specifies the name pattern to for individual data files. |
| `filepath` | string | No | Specifies the name pattern for directory. |
| `prefix` | string | No | Specifies the base directory within the bucket. |

