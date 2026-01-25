# email-security_Domain

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_delivery_modes` | email-security_DeliveryMode[] | Yes |  |
| `authorization` | any | No |  |
| `created_at` | string (date-time) | Yes |  |
| `dmarc_status` | any | No |  |
| `domain` | string | Yes |  |
| `drop_dispositions` | email-security_DispositionLabel[] | Yes |  |
| `emails_processed` | any | No |  |
| `folder` | any | No |  |
| `id` | integer (int32) | Yes | The unique identifier for the domain. |
| `inbox_provider` | any | No |  |
| `integration_id` | string (uuid) | No |  |
| `ip_restrictions` | string[] | Yes |  |
| `last_modified` | string (date-time) | Yes |  |
| `lookback_hops` | integer (int32) | Yes |  |
| `o365_tenant_id` | string | No |  |
| `regions` | string[] | Yes |  |
| `require_tls_inbound` | boolean | No |  |
| `require_tls_outbound` | boolean | No |  |
| `spf_status` | any | No |  |
| `transport` | string | Yes |  |

