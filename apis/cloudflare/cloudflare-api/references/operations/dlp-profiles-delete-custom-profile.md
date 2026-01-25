# DELETE /accounts/{account_id}/dlp/profiles/custom/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Delete custom profile**
**Operation ID:** `dlp-profiles-delete-custom-profile`

Deletes a DLP custom profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete custom profile response. |
| 4XX | Delete custom profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
