# PATCH /accounts/{account_id}/dns_settings

**Resource:** [DNS Settings for an Account](../resources/DNS-Settings-for-an-Account.md)
**Update DNS Settings**
**Operation ID:** `dns-settings-for-an-account-update-dns-settings`

Update DNS settings for an account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-settings_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-settings_account_settings_patch](../schemas/dns-settings/dns-settings-account-settings-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Show DNS Settings response |
| 4XX | Show DNS Settings response failure |

**Success Response Schema:**

[dns-settings_dns_response_single](../schemas/dns-settings/dns-settings-dns-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
