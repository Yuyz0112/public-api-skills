# POST /v1/charges

**Resource:** [charges](../resources/charges.md)
**Operation ID:** `PostCharges`

<p>This method is no longer recommended—use the <a href="/docs/api/payment_intents">Payment Intents API</a>
to initiate a new payment instead. Confirmation of the PaymentIntent creates the <code>Charge</code>
object used to request payment.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[charge](../schemas/charge/charge.md)

