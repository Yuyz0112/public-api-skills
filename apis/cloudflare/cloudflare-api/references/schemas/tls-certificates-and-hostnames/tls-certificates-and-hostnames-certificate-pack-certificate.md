# tls-certificates-and-hostnames_certificate_pack_certificate

An individual certificate within a certificate pack.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bundle_method` | string | No | Certificate bundle method. |
| `expires_on` | string (date-time) | No | When the certificate from the authority expires. |
| `geo_restrictions` | object | No | Specify the region where your private key can be held locally. |
| `hosts` | string[] | Yes | Hostnames covered by this certificate. |
| `id` | string | Yes | Certificate identifier. |
| `issuer` | string | No | The certificate authority that issued the certificate. |
| `modified_on` | string (date-time) | No | When the certificate was last modified. |
| `priority` | number | No | The order/priority in which the certificate will be used. |
| `signature` | string | No | The type of hash used for the certificate. |
| `status` | string | Yes | Certificate status. |
| `uploaded_on` | string (date-time) | No | When the certificate was uploaded to Cloudflare. |
| `zone_id` | [tls-certificates-and-hostnames_identifier](tls-certificates-and-hostnames-identifier.md) | No |  |

## Nested Fields

### `geo_restrictions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | enum: us, eu, highest_security | No |  |

