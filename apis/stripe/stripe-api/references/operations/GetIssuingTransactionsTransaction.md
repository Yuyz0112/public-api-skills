# GET /v1/issuing/transactions/{transaction}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve a transaction**
**Operation ID:** `GetIssuingTransactionsTransaction`

<p>Retrieves an Issuing <code>Transaction</code> object.</p>

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

[issuing.transaction](../schemas/issuing-transaction/issuing-transaction.md)

