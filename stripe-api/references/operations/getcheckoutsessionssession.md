# GET /v1/checkout/sessions/{session}

**Resource:** [checkout](../resources/checkout.md)
**Retrieve a Checkout Session**
**Operation ID:** `GetCheckoutSessionsSession`

<p>Retrieves a Checkout Session object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

