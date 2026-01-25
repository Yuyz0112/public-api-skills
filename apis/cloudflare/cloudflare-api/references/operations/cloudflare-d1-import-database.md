# POST /accounts/{account_id}/d1/database/{database_id}/import

**Resource:** [D1](../resources/D1.md)
**Import SQL into your D1 Database**
**Operation ID:** `cloudflare-d1-import-database`

Generates a temporary URL for uploading an SQL file to, then instructing the D1 to import it
and polling it for status updates. Imports block the D1 for their duration.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `database_id` | path | d1_database-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful action. Import is either ready to start, under way, or finished (succeeded or failed). |
| 202 | Polled successfully, task is currently running |
| 4XX | Poll failed (API error) |

## Security

- **api_token**
- **api_email**
- **api_key**
