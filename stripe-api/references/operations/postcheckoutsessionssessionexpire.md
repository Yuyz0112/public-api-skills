# POST /v1/checkout/sessions/{session}/expire

**Resource:** [checkout](../resources/checkout.md)
**Expire a Checkout Session**
**Operation ID:** `PostCheckoutSessionsSessionExpire`

<p>A Checkout Session can be expired when it is in one of these statuses: <code>open</code> </p>

<p>After it expires, a customer can’t complete a Checkout Session and customers loading the Checkout Session see a message saying the Checkout Session is expired.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `session` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[checkout.session](../schemas/checkout-session/checkout-session.md)

