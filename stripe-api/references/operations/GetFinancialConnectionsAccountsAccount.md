# GET /v1/financial_connections/accounts/{account}

**Resource:** [financial_connections](../resources/financial-connections.md)
**Retrieve an Account**
**Operation ID:** `GetFinancialConnectionsAccountsAccount`

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

