# POST /accounts/{account_id}/d1/database/{database_id}/export

**Resource:** [D1](../resources/D1.md)
**Export D1 Database as SQL**
**Operation ID:** `cloudflare-d1-export-database`

Returns a URL where the SQL contents of your D1 can be downloaded. Note: this process may take
some time for larger DBs, during which your D1 will be unavailable to serve queries. To avoid
blocking your DB unnecessarily, an in-progress export must be continually polled or will automatically cancel.


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
| 200 | Polled successfully, task no longer running (errored or complete) |
| 202 | Polled successfully, task is currently running |
| 4XX | Poll failed (API error) |

## Security

- **api_token**
- **api_email**
- **api_key**
