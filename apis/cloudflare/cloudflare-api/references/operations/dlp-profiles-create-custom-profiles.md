# POST /accounts/{account_id}/dlp/profiles/custom

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**Create custom profile**
**Operation ID:** `dlp-profiles-create-custom-profiles`

Creates a DLP custom profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

A new profile to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_NewCustomProfile](../schemas/dlp/dlp-NewCustomProfile.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | New custom profile response. |
| 4XX | New custom profile failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
