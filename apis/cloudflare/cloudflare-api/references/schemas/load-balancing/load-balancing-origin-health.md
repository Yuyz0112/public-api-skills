# load-balancing_origin-health

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip` | object | No |  |

## Nested Fields

### `ip`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `failure_reason` | string | No | Failure reason. |
| `healthy` | boolean | No | Origin health status. |
| `response_code` | number | No | Response code from origin health check. |
| `rtt` | string | No | Origin RTT (Round Trip Time) response. |

