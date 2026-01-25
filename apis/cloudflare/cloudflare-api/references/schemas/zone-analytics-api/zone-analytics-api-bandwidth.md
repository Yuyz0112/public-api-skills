# zone-analytics-api_bandwidth

Breakdown of totals for bandwidth in the form of bytes.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | integer | No | The total number of bytes served within the time frame. |
| `cached` | integer | No | The number of bytes that were cached (and served) by Cloudflare. |
| `content_type` | object | No | A variable list of key/value pairs where the key represents the type of content served, and the value is the number in bytes served. |
| `country` | object | No | A variable list of key/value pairs where the key is a two-digit country code and the value is the number of bytes served to that country. |
| `ssl` | object | No | A break down of bytes served over HTTPS. |
| `ssl_protocols` | object | No | A breakdown of requests by their SSL protocol. |
| `uncached` | integer | No | The number of bytes that were fetched and served from the origin server. |

## Nested Fields

### `ssl`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `encrypted` | integer | No | The number of bytes served over HTTPS. |
| `unencrypted` | integer | No | The number of bytes served over HTTP. |

### `ssl_protocols`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `TLSv1` | integer | No | The number of requests served over TLS v1.0. |
| `TLSv1.1` | integer | No | The number of requests served over TLS v1.1. |
| `TLSv1.2` | integer | No | The number of requests served over TLS v1.2. |
| `TLSv1.3` | integer | No | The number of requests served over TLS v1.3. |
| `none` | integer | No | The number of requests served over HTTP. |

