# GET /v1/financial_connections/transactions/{transaction}

**Resource:** [financial_connections](../resources/financial-connections.md)
**Retrieve a Transaction**
**Operation ID:** `GetFinancialConnectionsTransactionsTransaction`

<p>Retrieves the details of a Financial Connections <code>Transaction</code></p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `transaction` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[financial_connections.transaction](../schemas/financial/financial-connections-transaction.md)

