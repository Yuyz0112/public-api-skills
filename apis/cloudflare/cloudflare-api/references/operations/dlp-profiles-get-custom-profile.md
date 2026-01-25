# GET /accounts/{account_id}/dlp/profiles/custom/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Get custom profile**
**Operation ID:** `dlp-profiles-get-custom-profile`

Fetches a custom DLP profile by id.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Custom profile response. |
| 4XX | Custom profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
