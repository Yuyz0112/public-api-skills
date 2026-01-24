# POST /v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Update an OutboundTransfer**
**Operation ID:** `PostTestHelpersTreasuryOutboundTransfersOutboundTransfer`

<p>Updates a test mode created OutboundTransfer with tracking details. The OutboundTransfer must not be cancelable, and cannot be in the <code>canceled</code> or <code>failed</code> states.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `outbound_transfer` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.outbound_transfer](../schemas/treasury-outbound/treasury-outbound-transfer.md)

