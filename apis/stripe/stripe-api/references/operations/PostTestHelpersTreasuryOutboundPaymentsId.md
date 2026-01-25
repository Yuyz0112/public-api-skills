# POST /v1/test_helpers/treasury/outbound_payments/{id}

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Update an OutboundPayment**
**Operation ID:** `PostTestHelpersTreasuryOutboundPaymentsId`

<p>Updates a test mode created OutboundPayment with tracking details. The OutboundPayment must not be cancelable, and cannot be in the <code>canceled</code> or <code>failed</code> states.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

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

