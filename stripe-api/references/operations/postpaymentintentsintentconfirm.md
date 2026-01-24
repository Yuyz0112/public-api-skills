# POST /v1/payment_intents/{intent}/confirm

**Resource:** [payment_intents](../resources/payment-intents.md)
**Confirm a PaymentIntent**
**Operation ID:** `PostPaymentIntentsIntentConfirm`

<p>Confirm that your customer intends to pay with current or provided
payment method. Upon confirmation, the PaymentIntent will attempt to initiate
a payment.</p>

<p>If the selected payment method requires additional authentication steps, the
PaymentIntent will transition to the <code>requires_action</code> status and
suggest additional actions via <code>next_action</code>. If payment fails,
the PaymentIntent transitions to the <code>requires_payment_method</code> status or the
<code>canceled</code> status if the confirmation limit is reached. If
payment succeeds, the PaymentIntent will transition to the <code>succeeded</code>
status (or <code>requires_capture</code>, if <code>capture_method</code> is set to <code>manual</code>).</p>

<p>If the <code>confirmation_method</code> is <code>automatic</code>, payment may be attempted
using our <a href="/docs/stripe-js/reference#stripe-handle-card-payment">client SDKs</a>
and the PaymentIntent’s <a href="#payment_intent_object-client_secret">client_secret</a>.
After <code>next_action</code>s are handled by the client, no additional
confirmation is required to complete the payment.</p>

<p>If the <code>confirmation_method</code> is <code>manual</code>, all payment attempts must be
initiated using a secret key.</p>

<p>If any actions are required for the payment, the PaymentIntent will
return to the <code>requires_confirmation</code> state
after those actions are completed. Your server needs to then
explicitly re-confirm the PaymentIntent to initiate the next payment
attempt.</p>

<p>There is a variable upper limit on how many times a PaymentIntent can be confirmed.
After this limit is reached, any further calls to this endpoint will
transition the PaymentIntent to the <code>canceled</code> state.</p>

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

