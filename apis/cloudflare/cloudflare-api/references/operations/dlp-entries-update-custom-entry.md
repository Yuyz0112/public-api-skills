# PUT /accounts/{account_id}/dlp/entries/custom/{entry_id}

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**Update custom entry**
**Operation ID:** `dlp-entries-update-custom-entry`

Updates a DLP custom entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Request Body

Update to be applied to the entry.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_CustomEntryUpdate](../schemas/dlp/dlp-CustomEntryUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update entry response. |
| 4XX | Update entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
