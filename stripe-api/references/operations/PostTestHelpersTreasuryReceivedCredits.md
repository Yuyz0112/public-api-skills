# POST /v1/test_helpers/treasury/received_credits

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Create a ReceivedCredit**
**Operation ID:** `PostTestHelpersTreasuryReceivedCredits`

<p>Use this endpoint to simulate a test mode ReceivedCredit initiated by a third party. In live mode, you can’t directly create ReceivedCredits initiated by third parties.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.received_credit](../schemas/treasury-received/treasury-received-credit.md)

