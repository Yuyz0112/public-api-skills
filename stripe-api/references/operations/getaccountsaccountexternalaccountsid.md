# GET /v1/accounts/{account}/external_accounts/{id}

**Resource:** [accounts](../resources/accounts.md)
**Retrieve an external account**
**Operation ID:** `GetAccountsAccountExternalAccountsId`

<p>Retrieve a specified external account for a given account.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes | Unique identifier for the external account to be retrieved. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[external_account](../schemas/external/external-account.md)

