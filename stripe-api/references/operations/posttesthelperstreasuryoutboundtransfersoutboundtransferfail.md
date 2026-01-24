# POST /v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/fail

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Fail an OutboundTransfer**
**Operation ID:** `PostTestHelpersTreasuryOutboundTransfersOutboundTransferFail`

<p>Transitions a test mode created OutboundTransfer to the <code>failed</code> status. The OutboundTransfer must already be in the <code>processing</code> state.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `outbound_transfer` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.outbound_transfer](../schemas/treasury-outbound/treasury-outbound-transfer.md)

