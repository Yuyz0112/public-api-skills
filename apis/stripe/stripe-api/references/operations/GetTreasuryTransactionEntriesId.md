# GET /v1/treasury/transaction_entries/{id}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a TransactionEntry**
**Operation ID:** `GetTreasuryTransactionEntriesId`

<p>Retrieves a TransactionEntry object.</p>

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

[treasury.transaction_entry](../schemas/treasury-transaction/treasury-transaction-entry.md)

