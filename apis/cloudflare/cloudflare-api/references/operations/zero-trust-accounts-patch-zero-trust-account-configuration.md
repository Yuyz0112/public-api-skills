# PATCH /accounts/{account_id}/gateway/configuration

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Patch Zero Trust account configuration**
**Operation ID:** `zero-trust-accounts-patch-zero-trust-account-configuration`

Update (PATCH) a single subcollection of settings such as `antivirus`, `tls_decrypt`, `activity_log`, `block_page`, `browser_isolation`, `fips`, `body_scanning`, or `certificate` without updating the entire configuration object. This endpoint returns an error if any settings collection lacks proper configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zero-trust-gateway_gateway-account-settings](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-settings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Zero Trust account configuration response. |
| 4XX | Zero Trust account configuration response failure. |

**Success Response Schema:**

[zero-trust-gateway_gateway_account_config](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-config.md)

## Security

- **api_email**
- **api_key**
- **api_token**
