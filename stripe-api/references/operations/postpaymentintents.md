# POST /v1/payment_intents

**Resource:** [payment_intents](../resources/payment-intents.md)
**Create a PaymentIntent**
**Operation ID:** `PostPaymentIntents`

<p>Creates a PaymentIntent object.</p>

<p>After the PaymentIntent is created, attach a payment method and <a href="/docs/api/payment_intents/confirm">confirm</a>
to continue the payment. Learn more about <a href="/docs/payments/payment-intents">the available payment flows
with the Payment Intents API</a>.</p>

<p>When you use <code>confirm=true</code> during creation, it’s equivalent to creating
and confirming the PaymentIntent in the same call. You can use any parameters
available in the <a href="/docs/api/payment_intents/confirm">confirm API</a> when you supply
<code>confirm=true</code>.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_intent](../schemas/payment/payment-intent.md)

