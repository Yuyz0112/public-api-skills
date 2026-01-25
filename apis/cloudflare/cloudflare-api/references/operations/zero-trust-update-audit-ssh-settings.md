# PUT /accounts/{account_id}/gateway/audit_ssh_settings

**Resource:** [Zero Trust SSH Settings](../resources/Zero-Trust-SSH-Settings.md)
**Update Zero Trust SSH settings**
**Operation ID:** `zero-trust-update-audit-ssh-settings`

Update Zero Trust Audit SSH and SSH with Access for Infrastructure settings for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Zero Trust SSH settings response. |
| 4XX | Update Zero Trust SSH settings response failure. |

**Success Response Schema:**

[zero-trust-gateway_audit_ssh_settings_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-audit-ssh-settings-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
