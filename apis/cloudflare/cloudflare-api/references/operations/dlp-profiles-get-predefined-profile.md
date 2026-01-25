# GET /accounts/{account_id}/dlp/profiles/predefined/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Get predefined profile**
**Operation ID:** `dlp-profiles-get-predefined-profile`

Fetches a predefined DLP profile by id.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Predefined profile response. |
| 4XX | Predefined profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
