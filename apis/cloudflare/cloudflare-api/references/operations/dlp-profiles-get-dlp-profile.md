# GET /accounts/{account_id}/dlp/profiles/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Get DLP Profile**
**Operation ID:** `dlp-profiles-get-dlp-profile`

Fetches a DLP profile by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get profile response. |
| 4XX | Get profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
