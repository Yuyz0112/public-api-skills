# POST /accounts/{account_id}/dlp/entries/predefined

**Resource:** [DLP Predefined Entries](../resources/DLP-Predefined-Entries.md)
**Create predefined entry**
**Operation ID:** `dlp-entries-create-predefined-entry`

Predefined entries can't be created, this will update an existing predefined entry.
This is needed for our generated terraform API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

This endpoint will update an existing predefined entry. It is not possible to create new predefined entries.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_NewPredefinedEntry](../schemas/dlp/dlp-NewPredefinedEntry.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create predefined entry response. |
| 4XX | Create entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
