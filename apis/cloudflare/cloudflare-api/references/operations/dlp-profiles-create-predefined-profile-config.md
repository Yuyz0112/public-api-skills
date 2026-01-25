# POST /accounts/{account_id}/dlp/profiles/predefined/{profile_id}/config

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Create predefined profile**
**Operation ID:** `dlp-profiles-create-predefined-profile-config`

This is similar to `update_predefined` but only returns entries that are enabled.
This is needed for our terraform API
Creates a DLP predefined profile. Only supports enabling/disabling entries.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `profile_id` | path | string (uuid) | Yes |  |

## Request Body

Predefined profiles can not be created. This endpoint will only update an existing predefined profiles settings.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_PredefinedProfileConfigUpdate](../schemas/dlp/dlp-PredefinedProfileConfigUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create predefined profile response. |
| 4XX | Create predefined profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
