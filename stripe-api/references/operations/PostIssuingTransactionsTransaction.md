# POST /v1/issuing/transactions/{transaction}

**Resource:** [issuing](../resources/issuing.md)
**Update a transaction**
**Operation ID:** `PostIssuingTransactionsTransaction`

<p>Updates the specified Issuing <code>Transaction</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

