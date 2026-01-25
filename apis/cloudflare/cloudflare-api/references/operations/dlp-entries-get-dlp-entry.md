# GET /accounts/{account_id}/dlp/entries/{entry_id}

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**Get DLP Entry**
**Operation ID:** `dlp-entries-get-dlp-entry`

Fetches a DLP entry by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `entry_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get entry response. |
| 4XX | Get entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
