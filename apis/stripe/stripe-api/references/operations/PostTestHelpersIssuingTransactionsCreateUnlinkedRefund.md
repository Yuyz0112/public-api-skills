# POST /v1/test_helpers/issuing/transactions/create_unlinked_refund

**Resource:** [test_helpers](../resources/test-helpers.md)
**Create a test-mode unlinked refund**
**Operation ID:** `PostTestHelpersIssuingTransactionsCreateUnlinkedRefund`

<p>Allows the user to refund an arbitrary amount, also known as a unlinked refund.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.transaction](../schemas/issuing-transaction/issuing-transaction.md)

