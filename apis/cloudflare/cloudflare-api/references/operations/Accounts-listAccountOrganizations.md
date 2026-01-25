# GET /accounts/{account_id}/organizations

**Resource:** [Accounts](../resources/Accounts.md)
**List account organizations**
**Operation ID:** `Accounts_listAccountOrganizations`

Retrieve a list of the organizations that "contain" this account or are
managing it.

The returned list will be in order from "root" to "leaf", where the "leaf"
will be the organization that _immediately_ contains the specified
account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
