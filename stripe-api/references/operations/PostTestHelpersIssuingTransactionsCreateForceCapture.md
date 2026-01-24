# POST /v1/test_helpers/issuing/transactions/create_force_capture

**Resource:** [test_helpers](../resources/test-helpers.md)
**Create a test-mode force capture**
**Operation ID:** `PostTestHelpersIssuingTransactionsCreateForceCapture`

<p>Allows the user to capture an arbitrary amount, also known as a forced capture.</p>

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

