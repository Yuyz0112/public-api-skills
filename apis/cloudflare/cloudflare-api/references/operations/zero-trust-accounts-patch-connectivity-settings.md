# PATCH /accounts/{account_id}/zerotrust/connectivity_settings

**Resource:** [Zero Trust Connectivity Settings](../resources/Zero-Trust-Connectivity-Settings.md)
**Updates the Zero Trust Connectivity Settings**
**Operation ID:** `zero-trust-accounts-patch-connectivity-settings`

Updates the Zero Trust Connectivity Settings for the given account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Zero Trust Connectivity Settings response |
| 4XX | Update Zero Trust Connectivity Settings response failure |

**Success Response Schema:**

[tunnel_zero_trust_connectivity_settings_response](../schemas/tunnel/tunnel-zero-trust-connectivity-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
