# POST /v1/checkout/sessions

**Resource:** [checkout](../resources/checkout.md)
**Create a Checkout Session**
**Operation ID:** `PostCheckoutSessions`

<p>Creates a Checkout Session object.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[checkout.session](../schemas/checkout-session/checkout-session.md)

