# POST /accounts/{account_id}/gateway/audit_ssh_settings/rotate_seed

**Resource:** [Zero Trust SSH Settings](../resources/Zero-Trust-SSH-Settings.md)
**Rotate Zero Trust SSH account seed**
**Operation ID:** `zero-trust-rotate-ssh-account-seed`

Rotate the SSH account seed that generates the host key identity when connecting through the Cloudflare SSH Proxy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rotate Zero Trust SSH account seed response. |
| 4XX | Rotate Zero Trust SSH account seed response failure. |

**Success Response Schema:**

[zero-trust-gateway_audit_ssh_settings_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-audit-ssh-settings-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
