# POST /v1/test_helpers/issuing/transactions/{transaction}/refund

**Resource:** [test_helpers](../resources/test-helpers.md)
**Refund a test-mode transaction**
**Operation ID:** `PostTestHelpersIssuingTransactionsTransactionRefund`

<p>Refund a test-mode Transaction.</p>

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

