# zero-trust-gateway_custom-certificate-settings

Specify custom certificate settings for BYO-PKI. This field is deprecated; use `certificate` instead.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `binding_status` | string | No | Indicate the internal certificate status. |
| `enabled` | boolean | Yes | Specify whether to enable a custom certificate authority for signing Gateway traffic. |
| `id` | string | No | Specify the UUID of the certificate (ID from MTLS certificate store). |
| `updated_at` | string (date-time) | No |  |

