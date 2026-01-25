# POST /v1/treasury/credit_reversals

**Resource:** [treasury](../resources/treasury.md)
**Create a CreditReversal**
**Operation ID:** `PostTreasuryCreditReversals`

<p>Reverses a ReceivedCredit and creates a CreditReversal object.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.credit_reversal](../schemas/treasury-credit/treasury-credit-reversal.md)

