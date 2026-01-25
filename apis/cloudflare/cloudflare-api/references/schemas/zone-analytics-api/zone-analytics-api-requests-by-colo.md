# zone-analytics-api_requests_by_colo

Breakdown of totals for requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | integer | No | Total number of requests served. |
| `cached` | integer | No | Total number of cached requests served. |
| `country` | object | No | Key/value pairs where the key is a two-digit country code and the value is the number of requests served to that country. |
| `http_status` | object | No | A variable list of key/value pairs where the key is a HTTP status code and the value is the number of requests with that code served. |
| `uncached` | integer | No | Total number of requests served from the origin. |

