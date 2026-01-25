# POST /accounts/{account_id}/dlp/email/account_mapping

**Resource:** [DLP Email](../resources/DLP-Email.md)
**Create mapping**
**Operation ID:** `dlp-email-scanner-create-account-mapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

Account mapping.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_UpdateAddinAccountMapping](../schemas/dlp/dlp-UpdateAddinAccountMapping.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | New Email Scanner Account Mapping response. |
| 4XX | New Email Scanner Account Mapping failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
