# POST /v1/charges/{charge}/capture

**Resource:** [charges](../resources/charges.md)
**Capture a payment**
**Operation ID:** `PostChargesChargeCapture`

<p>Capture the payment of an existing, uncaptured charge that was created with the <code>capture</code> option set to false.</p>

<p>Uncaptured payments expire a set number of days after they are created (<a href="/docs/charges/placing-a-hold">7 by default</a>), after which they are marked as refunded and capture attempts will fail.</p>

<p>Don’t use this method to capture a PaymentIntent-initiated charge. Use <a href="/docs/api/payment_intents/capture">Capture a PaymentIntent</a>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `charge` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[charge](../schemas/charge/charge.md)

