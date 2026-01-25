# DELETE /accounts/{account_id}/dlp/entries/predefined/{entry_id}

**Resource:** [DLP Predefined Entries](../resources/DLP-Predefined-Entries.md)
**Delete predefined entry**
**Operation ID:** `dlp-entries-delete-predefined-entry`

This is a no-op as predefined entires can't be deleted but is needed for our generated terraform API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete predefined entry response. |
| 4XX | Delete entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
