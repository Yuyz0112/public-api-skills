# POST /accounts/{account_id}/dlp/entries/integration

**Resource:** [DLP Integration Entries](../resources/DLP-Integration-Entries.md)
**Create integration entry**
**Operation ID:** `dlp-entries-create-integration-entry`

Integration entries can't be created, this will update an existing integration entry.
This is needed for our generated terraform API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

This endpoint will update an existing integration entry. It is not possible to create new integration entries.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_NewPredefinedEntry](../schemas/dlp/dlp-NewPredefinedEntry.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create integration entry response. |
| 4XX | Create entry failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
