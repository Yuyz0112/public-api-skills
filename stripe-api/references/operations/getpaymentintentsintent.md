# GET /v1/payment_intents/{intent}

**Resource:** [payment_intents](../resources/payment-intents.md)
**Retrieve a PaymentIntent**
**Operation ID:** `GetPaymentIntentsIntent`

<p>Retrieves the details of a PaymentIntent that has previously been created. </p>

<p>You can retrieve a PaymentIntent client-side using a publishable key when the <code>client_secret</code> is in the query string. </p>

<p>If you retrieve a PaymentIntent with a publishable key, it only returns a subset of properties. Refer to the <a href="#payment_intent_object">payment intent</a> object reference for more details.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `client_secret` | query | string | No | The client secret of the PaymentIntent. We require it if you use a publishable key to retrieve the source. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

