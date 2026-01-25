# POST /v1/payment_intents/{intent}/apply_customer_balance

**Resource:** [payment_intents](../resources/payment-intents.md)
**Reconcile a customer_balance PaymentIntent**
**Operation ID:** `PostPaymentIntentsIntentApplyCustomerBalance`

<p>Manually reconcile the remaining amount for a <code>customer_balance</code> PaymentIntent.</p>

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

