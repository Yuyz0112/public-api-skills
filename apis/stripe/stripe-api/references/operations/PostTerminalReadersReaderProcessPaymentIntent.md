# POST /v1/terminal/readers/{reader}/process_payment_intent

**Resource:** [terminal](../resources/terminal.md)
**Hand-off a PaymentIntent to a Reader**
**Operation ID:** `PostTerminalReadersReaderProcessPaymentIntent`

<p>Initiates a payment flow on a Reader. See <a href="/docs/terminal/payments/collect-card-payment?terminal-sdk-platform=server-driven&process=immediately#process-payment">process the payment</a> for more details.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `reader` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.reader](../schemas/terminal-reader/terminal-reader.md)

