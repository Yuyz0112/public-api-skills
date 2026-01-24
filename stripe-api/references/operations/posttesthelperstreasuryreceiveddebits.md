# POST /v1/test_helpers/treasury/received_debits

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Create a ReceivedDebit**
**Operation ID:** `PostTestHelpersTreasuryReceivedDebits`

<p>Use this endpoint to simulate a test mode ReceivedDebit initiated by a third party. In live mode, you can’t directly create ReceivedDebits initiated by third parties.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.received_debit](../schemas/treasury-received/treasury-received-debit.md)

