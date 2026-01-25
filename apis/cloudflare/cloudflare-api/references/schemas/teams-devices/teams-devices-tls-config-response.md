# teams-devices_tls_config_response

The Managed Network TLS Config Response.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha256` | string | No | The SHA-256 hash of the TLS certificate presented by the host found at tls_sockaddr. If absent, regular certificate verification (trusted roots, valid timestamp, etc) will be used to validate the certificate. |
| `tls_sockaddr` | string | Yes | A network address of the form "host:port" that the WARP client will use to detect the presence of a TLS host. |

