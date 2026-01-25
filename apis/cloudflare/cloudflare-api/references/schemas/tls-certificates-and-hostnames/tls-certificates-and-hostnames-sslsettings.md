# tls-certificates-and-hostnames_sslsettings

SSL specific settings.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ciphers` | string[] | No | An allowlist of ciphers for TLS termination. These ciphers must be in the BoringSSL format. |
| `early_hints` | enum: on, off | No | Whether or not Early Hints is enabled. |
| `http2` | enum: on, off | No | Whether or not HTTP2 is enabled. |
| `min_tls_version` | enum: 1.0, 1.1, 1.2... | No | The minimum TLS version supported. |
| `tls_1_3` | enum: on, off | No | Whether or not TLS 1.3 is enabled. |

