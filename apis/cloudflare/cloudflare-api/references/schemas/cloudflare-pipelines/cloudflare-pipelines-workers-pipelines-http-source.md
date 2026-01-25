# cloudflare-pipelines_workers_pipelines_http_source

[DEPRECATED] HTTP source configuration. Use the new streams API instead.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `authentication` | boolean | No | Specifies whether authentication is required to send to this pipeline via HTTP. |
| `cors` | object | No |  |
| `format` | enum: json | Yes | Specifies the format of source data. |
| `type` | string | Yes |  |

## Nested Fields

### `cors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `origins` | string[] | No | Specifies allowed origins to allow Cross Origin HTTP Requests. |

