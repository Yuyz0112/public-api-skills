# POST /v1/radar/payment_evaluations

**Resource:** [radar](../resources/radar.md)
**Create a Payment Evaluation**
**Operation ID:** `PostRadarPaymentEvaluations`

<p>Request a Radar API fraud risk score from Stripe for a payment before sending it for external processor authorization.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[radar.payment_evaluation](../schemas/radar-payment/radar-payment-evaluation.md)

