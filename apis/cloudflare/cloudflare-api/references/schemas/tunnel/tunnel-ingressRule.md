# tunnel_ingressRule

Public hostname

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hostname` | string | Yes | Public hostname for this service. |
| `originRequest` | [tunnel_originRequest](tunnel-originRequest.md) | No |  |
| `path` | string | No | Requests with this path route to this public hostname. |
| `service` | string | Yes | Protocol and address of destination server. Supported protocols: http://, https://, unix://, tcp://, ssh://, rdp://, unix+tls://, smb://. Alternatively can return a HTTP status code http_status:[code] e.g. 'http_status:404'.
 |

