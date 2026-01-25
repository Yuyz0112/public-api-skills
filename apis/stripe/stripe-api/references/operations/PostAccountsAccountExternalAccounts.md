# POST /v1/accounts/{account}/external_accounts

**Resource:** [accounts](../resources/accounts.md)
**Create an external account**
**Operation ID:** `PostAccountsAccountExternalAccounts`

<p>Create an external account for a given account.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[external_account](../schemas/external/external-account.md)

