# POST /v1/treasury/outbound_payments/{id}/cancel

**Resource:** [treasury](../resources/treasury.md)
**Cancel an OutboundPayment**
**Operation ID:** `PostTreasuryOutboundPaymentsIdCancel`

<p>Cancel an OutboundPayment.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.outbound_payment](../schemas/treasury-outbound/treasury-outbound-payment.md)

