# PUT /accounts/{account_id}/dlp/entries/integration/{entry_id}

**Resource:** [DLP Integration Entries](../resources/DLP-Integration-Entries.md)
**Update integration entry**
**Operation ID:** `dlp-entries-update-integration-entry`

Updates a DLP entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Request Body

Enable or disable integration entry in owning profile.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_PredefinedEntryUpdate](../schemas/dlp/dlp-PredefinedEntryUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update integration entry response. |
| 4XX | Update entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
