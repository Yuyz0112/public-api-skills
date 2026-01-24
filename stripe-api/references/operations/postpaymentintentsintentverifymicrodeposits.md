# POST /v1/payment_intents/{intent}/verify_microdeposits

**Resource:** [payment_intents](../resources/payment-intents.md)
**Verify microdeposits on a PaymentIntent**
**Operation ID:** `PostPaymentIntentsIntentVerifyMicrodeposits`

<p>Verifies microdeposits on a PaymentIntent object.</p>

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

