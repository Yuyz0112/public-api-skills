# PUT /accounts/{account_id}/dlp/profiles/custom/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Update custom profile**
**Operation ID:** `dlp-profiles-update-custom-profile`

Updates a DLP custom profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Request Body

The updated parameters for the profile.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_CustomProfileUpdate](../schemas/dlp/dlp-CustomProfileUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update custom profile response. |
| 4XX | Update custom profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
