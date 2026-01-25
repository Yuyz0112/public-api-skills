# POST /accounts/{account_id}/dlp/profiles/predefined

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Create predefined profile**
**Operation ID:** `dlp-profiles-create-predefined-profile`

Creates a DLP predefined profile. Only supports enabling/disabling entries.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

Predefined profiles can not be created. This endpoint will only update an existing predefined profiles settings.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_NewPredefinedProfile](../schemas/dlp/dlp-NewPredefinedProfile.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create predefined profile response. |
| 4XX | Create predefined profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
