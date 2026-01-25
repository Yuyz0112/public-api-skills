# PUT /accounts/{account_id}/dlp/entries/predefined/{entry_id}

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**Update predefined entry**
**Operation ID:** `dlp-entries-update-predefined-entry`

Updates a DLP entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Request Body

Settings to enable or disable predefined entry in owning profile.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_PredefinedEntryUpdate](../schemas/dlp/dlp-PredefinedEntryUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update predefined entry response. |
| 4XX | Update entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
