# zone-analytics-api_bandwidth_by_colo

Breakdown of totals for bandwidth in the form of bytes.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | integer | No | The total number of bytes served within the time frame. |
| `cached` | integer | No | The number of bytes that were cached (and served) by Cloudflare. |
| `uncached` | integer | No | The number of bytes that were fetched and served from the origin server. |

