# zone-analytics-api_threats

Breakdown of totals for threats.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | integer | No | The total number of identifiable threats received over the time frame. |
| `country` | object | No | A list of key/value pairs where the key is a two-digit country code and the value is the number of malicious requests received from that country. |
| `type` | object | No | The list of key/value pairs where the key is a threat category and the value is the number of requests. |

