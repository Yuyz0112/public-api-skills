# POST /accounts/{account_id}/move

**Resource:** [Accounts](../resources/Accounts.md)
**Move account**
**Operation ID:** `Accounts_moveAccounts`

Move an account within an organization hierarchy or an account outside an organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

The destination organization ID is where the account is to be moved.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
