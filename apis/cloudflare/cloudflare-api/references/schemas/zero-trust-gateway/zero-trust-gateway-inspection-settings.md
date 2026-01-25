# zero-trust-gateway_inspection-settings

Define the proxy inspection mode.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mode` | enum: static, dynamic | No | Define the proxy inspection mode.   1. static: Gateway applies static inspection to HTTP on TCP(80). With TLS decryption on, Gateway inspects HTTPS traffic on TCP(443) and UDP(443).   2. dynamic: Gateway applies protocol detection to inspect HTTP and HTTPS traffic on any port. TLS decryption must remain on to inspect HTTPS traffic. |

