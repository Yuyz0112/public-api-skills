# POST /accounts/{account_id}/dlp/entries

**Resource:** [DLP Entries](../resources/DLP-Entries.md)
**Create custom entry**
**Operation ID:** `dlp-entries-create-entry`

Creates a DLP custom entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

A new entry to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_NewEntry](../schemas/dlp/dlp-NewEntry.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create new custom entry response. |
| 4XX | Create new custom entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
