# DELETE /accounts/{account_id}/dlp/profiles/predefined/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Delete predefined profile**
**Operation ID:** `dlp-profiles-delete-predefined-profile`

This is a no-op as predefined profiles can't be deleted but is needed for our generated terraform API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete predefined profile response. |
| 4XX | Delete predefined profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
