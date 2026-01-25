# zone-analytics-api_requests

Breakdown of totals for requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | integer | No | Total number of requests served. |
| `cached` | integer | No | Total number of cached requests served. |
| `content_type` | object | No | A variable list of key/value pairs where the key represents the type of content served, and the value is the number of requests. |
| `country` | object | No | A variable list of key/value pairs where the key is a two-digit country code and the value is the number of requests served to that country. |
| `http_status` | object | No | Key/value pairs where the key is a HTTP status code and the value is the number of requests served with that code. |
| `ssl` | object | No | A break down of requests served over HTTPS. |
| `ssl_protocols` | object | No | A breakdown of requests by their SSL protocol. |
| `uncached` | integer | No | Total number of requests served from the origin. |

## Nested Fields

### `ssl`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `encrypted` | integer | No | The number of requests served over HTTPS. |
| `unencrypted` | integer | No | The number of requests served over HTTP. |

### `ssl_protocols`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `TLSv1` | integer | No | The number of requests served over TLS v1.0. |
| `TLSv1.1` | integer | No | The number of requests served over TLS v1.1. |
| `TLSv1.2` | integer | No | The number of requests served over TLS v1.2. |
| `TLSv1.3` | integer | No | The number of requests served over TLS v1.3. |
| `none` | integer | No | The number of requests served over HTTP. |

