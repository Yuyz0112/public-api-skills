# PUT /accounts/{account_id}/dlp/profiles/predefined/{profile_id}

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Update predefined profile**
**Operation ID:** `dlp-profiles-update-predefined-profile`

Updates a DLP predefined profile. Only supports enabling/disabling entries.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Request Body

The updated parameters for the predefined profile.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_PredefinedProfileUpdate](../schemas/dlp/dlp-PredefinedProfileUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update predefined profile response. |
| 4XX | Update predefined profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
