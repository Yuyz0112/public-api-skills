# GET /organizations/{organization_id}/accounts

**Resource:** [Organizations](../resources/Organizations.md)
**Get organization accounts**
**Operation ID:** `Organizations_getAccounts`

Retrieve a list of accounts that belong to a specific organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes | The ID of the organization to retrieve a list of accounts for. |
| `account_pubname` | query | string | No | (case-insensitive) Filter the list of accounts to where the account_pubname is equal to
a particular string. |
| `account_pubname.startsWith` | query | string | No | (case-insensitive) Filter the list of accounts to where the account_pubname starts with
a particular string. |
| `account_pubname.endsWith` | query | string | No | (case-insensitive) Filter the list of accounts to where the account_pubname ends with
a particular string. |
| `account_pubname.contains` | query | string | No | (case-insensitive) Filter the list of accounts to where the account_pubname contains
a particular string. |
| `name` | query | string | No | (case-insensitive) Filter the list of accounts to where the name is equal to a
particular string. |
| `name.startsWith` | query | string | No | (case-insensitive) Filter the list of accounts to where the name starts with a
particular string. |
| `name.endsWith` | query | string | No | (case-insensitive) Filter the list of accounts to where the name ends with a particular
string. |
| `name.contains` | query | string | No | (case-insensitive) Filter the list of accounts to where the name contains a particular
string. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
