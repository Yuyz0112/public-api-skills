# GET /v1/tax/transactions/{transaction}

**Resource:** [tax](../resources/tax.md)
**Retrieve a transaction**
**Operation ID:** `GetTaxTransactionsTransaction`

<p>Retrieves a Tax <code>Transaction</code> object.</p>

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

[tax.transaction](../schemas/tax-transaction/tax-transaction.md)

