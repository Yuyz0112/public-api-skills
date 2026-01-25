# GET /v1/treasury/debit_reversals/{debit_reversal}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve a DebitReversal**
**Operation ID:** `GetTreasuryDebitReversalsDebitReversal`

<p>Retrieves a DebitReversal object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `debit_reversal` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.debit_reversal](../schemas/treasury-debit/treasury-debit-reversal.md)

