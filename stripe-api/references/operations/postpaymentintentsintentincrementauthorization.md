# POST /v1/payment_intents/{intent}/increment_authorization

**Resource:** [payment_intents](../resources/payment-intents.md)
**Increment an authorization**
**Operation ID:** `PostPaymentIntentsIntentIncrementAuthorization`

<p>Perform an incremental authorization on an eligible
<a href="/docs/api/payment_intents/object">PaymentIntent</a>. To be eligible, the
PaymentIntent’s status must be <code>requires_capture</code> and
<a href="/docs/api/charges/object#charge_object-payment_method_details-card_present-incremental_authorization_supported">incremental_authorization_supported</a>
must be <code>true</code>.</p>

<p>Incremental authorizations attempt to increase the authorized amount on
your customer’s card to the new, higher <code>amount</code> provided. Similar to the
initial authorization, incremental authorizations can be declined. A
single PaymentIntent can call this endpoint multiple times to further
increase the authorized amount.</p>

<p>If the incremental authorization succeeds, the PaymentIntent object
returns with the updated
<a href="/docs/api/payment_intents/object#payment_intent_object-amount">amount</a>.
If the incremental authorization fails, a
<a href="/docs/error-codes#card-declined">card_declined</a> error returns, and no other
fields on the PaymentIntent or Charge update. The PaymentIntent
object remains capturable for the previously authorized amount.</p>

<p>Each PaymentIntent can have a maximum of 10 incremental authorization attempts, including declines.
After it’s captured, a PaymentIntent can no longer be incremented.</p>

<p>Learn more about <a href="/docs/terminal/features/incremental-authorizations">incremental authorizations</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `intent` | path | string | Yes |  |

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

