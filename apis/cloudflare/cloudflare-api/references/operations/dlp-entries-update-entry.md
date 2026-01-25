# PUT /accounts/{account_id}/dlp/entries/{entry_id}

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**Update entry**
**Operation ID:** `dlp-entries-update-entry`

Updates a DLP entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Request Body

Update to be applied to the entry.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_EntryUpdate](../schemas/dlp/dlp-EntryUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update entry response. |
| 4XX | Update entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
