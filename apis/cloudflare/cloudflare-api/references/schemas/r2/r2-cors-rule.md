# r2_cors-rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed` | object | Yes | Object specifying allowed origins, methods and headers for this CORS rule. |
| `exposeHeaders` | string[] | No | Specifies the headers that can be exposed back, and accessed by, the JavaScript making the cross-origin request. If you need to access headers beyond the safelisted response headers, such as Content-Encoding or cf-cache-status, you must specify it here. |
| `id` | string | No | Identifier for this rule. |
| `maxAgeSeconds` | number | No | Specifies the amount of time (in seconds) browsers are allowed to cache CORS preflight responses. Browsers may limit this to 2 hours or less, even if the maximum value (86400) is specified. |

## Nested Fields

### `allowed`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `headers` | string[] | No | Specifies the value for the Access-Control-Allow-Headers header R2 sets when requesting objects in this bucket from a browser. Cross-origin requests that include custom headers (e.g. x-user-id) should specify these headers as AllowedHeaders. |
| `methods` | string[] | Yes | Specifies the value for the Access-Control-Allow-Methods header R2 sets when requesting objects in a bucket from a browser. |
| `origins` | string[] | Yes | Specifies the value for the Access-Control-Allow-Origin header R2 sets when requesting objects in a bucket from a browser. |

