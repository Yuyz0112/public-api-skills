# tls-certificates-and-hostnames_validation_record

Certificate's required validation record.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `emails` | string[] | No | The set of email addresses that the certificate authority (CA) will use to complete domain validation. |
| `http_body` | string | No | The content that the certificate authority (CA) will expect to find at the http_url during the domain validation. |
| `http_url` | string | No | The url that will be checked during domain validation. |
| `txt_name` | string | No | The hostname that the certificate authority (CA) will check for a TXT record during domain validation . |
| `txt_value` | string | No | The TXT record that the certificate authority (CA) will check during domain validation. |

