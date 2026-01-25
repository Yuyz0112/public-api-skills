# GET /accounts/{account_id}/dlp/entries

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**List all entries**
**Operation ID:** `dlp-entries-list-all-entries`

Lists all DLP entries in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all entries response. |
| 4XX | List all entries failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
