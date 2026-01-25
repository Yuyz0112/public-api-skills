# POST /v1/test_helpers/treasury/inbound_transfers/{id}/fail

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Fail an InboundTransfer**
**Operation ID:** `PostTestHelpersTreasuryInboundTransfersIdFail`

<p>Transitions a test mode created InboundTransfer to the <code>failed</code> status. The InboundTransfer must already be in the <code>processing</code> state.</p>

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

[treasury.inbound_transfer](../schemas/treasury-inbound/treasury-inbound-transfer.md)

