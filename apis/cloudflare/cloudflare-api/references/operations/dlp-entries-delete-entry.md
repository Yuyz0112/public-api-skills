# DELETE /accounts/{account_id}/dlp/entries/{entry_id}

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**Delete custom entry**
**Operation ID:** `dlp-entries-delete-entry`

Deletes a DLP custom entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete custom entry response. |
| 4XX | Delete custom entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
