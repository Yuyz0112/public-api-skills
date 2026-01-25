# tls-certificates-and-hostnames_hostname_association

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hostnames` | [tls-certificates-and-hostnames_schemas-hostnames](tls-certificates-and-hostnames-schemas-hostnames.md) | No |  |
| `mtls_certificate_id` | string | No | The UUID for a certificate that was uploaded to the mTLS Certificate Management endpoint. If no mtls_certificate_id is given, the hostnames will be associated to your active Cloudflare Managed CA. |

