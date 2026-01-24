# POST /v1/treasury/outbound_payments

**Resource:** [treasury](../resources/treasury.md)
**Create an OutboundPayment**
**Operation ID:** `PostTreasuryOutboundPayments`

<p>Creates an OutboundPayment.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.outbound_payment](../schemas/treasury-outbound/treasury-outbound-payment.md)

