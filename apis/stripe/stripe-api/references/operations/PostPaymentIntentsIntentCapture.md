# POST /v1/payment_intents/{intent}/capture

**Resource:** [payment_intents](../resources/payment-intents.md)
**Capture a PaymentIntent**
**Operation ID:** `PostPaymentIntentsIntentCapture`

<p>Capture the funds of an existing uncaptured PaymentIntent when its status is <code>requires_capture</code>.</p>

<p>Uncaptured PaymentIntents are cancelled a set number of days (7 by default) after their creation.</p>

<p>Learn more about <a href="/docs/payments/capture-later">separate authorization and capture</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `intent` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_intent](../schemas/payment/payment-intent.md)

