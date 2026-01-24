# GET /v1/linked_accounts/{account}

**Resource:** [linked_accounts](../resources/linked-accounts.md)
**Retrieve an Account**
**Operation ID:** `GetLinkedAccountsAccount`

<p>Retrieves the details of an Financial Connections <code>Account</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[financial_connections.account](../schemas/financial/financial-connections-account.md)

