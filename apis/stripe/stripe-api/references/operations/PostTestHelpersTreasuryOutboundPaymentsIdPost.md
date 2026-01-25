# POST /v1/test_helpers/treasury/outbound_payments/{id}/post

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Post an OutboundPayment**
**Operation ID:** `PostTestHelpersTreasuryOutboundPaymentsIdPost`

<p>Transitions a test mode created OutboundPayment to the <code>posted</code> status. The OutboundPayment must already be in the <code>processing</code> state.</p>

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

