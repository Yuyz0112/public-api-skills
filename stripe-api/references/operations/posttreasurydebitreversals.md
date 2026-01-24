# POST /v1/treasury/debit_reversals

**Resource:** [treasury](../resources/treasury.md)
**Create a DebitReversal**
**Operation ID:** `PostTreasuryDebitReversals`

<p>Reverses a ReceivedDebit and creates a DebitReversal object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.debit_reversal](../schemas/treasury-debit/treasury-debit-reversal.md)

