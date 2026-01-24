# POST /v1/test_helpers/terminal/readers/{reader}/present_payment_method

**Resource:** [test_helpers](../resources/test-helpers.md)
**Simulate presenting a payment method**
**Operation ID:** `PostTestHelpersTerminalReadersReaderPresentPaymentMethod`

<p>Presents a payment method on a simulated reader. Can be used to simulate accepting a payment, saving a card or refunding a transaction.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `reader` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.reader](../schemas/terminal-reader/terminal-reader.md)

