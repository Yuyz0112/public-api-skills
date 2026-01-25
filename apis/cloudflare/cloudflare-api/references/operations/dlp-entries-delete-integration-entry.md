# DELETE /accounts/{account_id}/dlp/entries/integration/{entry_id}

**Resource:** [DLP Integration Entries](../resources/DLP-Integration-Entries.md)
**Delete integration entry**
**Operation ID:** `dlp-entries-delete-integration-entry`

This is a no-op as integration entires can't be deleted but is needed for our generated terraform API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete integration entry response. |
| 4XX | Delete entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
