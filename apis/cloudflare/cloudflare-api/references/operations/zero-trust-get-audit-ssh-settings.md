# GET /accounts/{account_id}/gateway/audit_ssh_settings

**Resource:** [Zero Trust SSH Settings](../resources/Zero-Trust-SSH-Settings.md)
**Get Zero Trust SSH settings**
**Operation ID:** `zero-trust-get-audit-ssh-settings`

Retrieve all Zero Trust Audit SSH and SSH with Access for Infrastructure settings for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zero Trust SSH settings response. |
| 4XX | Get Zero Trust SSH settings response failure. |

**Success Response Schema:**

[zero-trust-gateway_audit_ssh_settings_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-audit-ssh-settings-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
