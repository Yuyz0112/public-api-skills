# POST /v1/checkout/sessions/{session}

**Resource:** [checkout](../resources/checkout.md)
**Update a Checkout Session**
**Operation ID:** `PostCheckoutSessionsSession`

<p>Updates a Checkout Session object.</p>

<p>Related guide: <a href="/payments/advanced/dynamic-updates">Dynamically update a Checkout Session</a></p>

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

