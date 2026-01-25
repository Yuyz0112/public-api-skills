# GET /v1/treasury/transactions/{id}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a Transaction**
**Operation ID:** `GetTreasuryTransactionsId`

<p>Retrieves the details of an existing Transaction.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.transaction](../schemas/treasury-transaction/treasury-transaction.md)

