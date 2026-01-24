# POST /v1/terminal/readers/{reader}/collect_payment_method

**Resource:** [terminal](../resources/terminal.md)
**Hand off a PaymentIntent to a Reader and collect card details**
**Operation ID:** `PostTerminalReadersReaderCollectPaymentMethod`

<p>Initiates a payment flow on a Reader and updates the PaymentIntent with card details before manual confirmation. See <a href="/docs/terminal/payments/collect-card-payment?terminal-sdk-platform=server-driven&process=inspect#collect-a-paymentmethod">Collecting a Payment method</a> for more details.</p>

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

