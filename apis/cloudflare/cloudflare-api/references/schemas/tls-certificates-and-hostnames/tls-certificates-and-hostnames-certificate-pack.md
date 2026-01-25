# tls-certificates-and-hostnames_certificate_pack

A certificate pack with all its properties.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `certificate_authority` | [tls-certificates-and-hostnames_schemas-certificate_authority](tls-certificates-and-hostnames-schemas-certificate-authority.md) | No |  |
| `certificates` | tls-certificates-and-hostnames_certificate_pack_certificate[] | Yes | Array of certificates in this pack. |
| `cloudflare_branding` | [tls-certificates-and-hostnames_cloudflare_branding](tls-certificates-and-hostnames-cloudflare-branding.md) | No |  |
| `hosts` | [tls-certificates-and-hostnames_schemas-hosts](tls-certificates-and-hostnames-schemas-hosts.md) | Yes |  |
| `id` | [tls-certificates-and-hostnames_identifier](tls-certificates-and-hostnames-identifier.md) | Yes |  |
| `primary_certificate` | [tls-certificates-and-hostnames_primary](tls-certificates-and-hostnames-primary.md) | No |  |
| `status` | [tls-certificates-and-hostnames_certificate-packs_components-schemas-status](tls-certificates-and-hostnames-certificate-packs-components-schemas-status.md) | Yes |  |
| `type` | [tls-certificates-and-hostnames_schemas-type](tls-certificates-and-hostnames-schemas-type.md) | Yes |  |
| `validation_errors` | object[] | No | Domain validation errors that have been received by the certificate authority (CA). |
| `validation_method` | [tls-certificates-and-hostnames_validation_method](tls-certificates-and-hostnames-validation-method.md) | No |  |
| `validation_records` | tls-certificates-and-hostnames_validation_record[] | No | Certificates' validation records. |
| `validity_days` | [tls-certificates-and-hostnames_validity_days](tls-certificates-and-hostnames-validity-days.md) | No |  |

## Nested Fields

### `validation_errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No | A domain validation error. |

