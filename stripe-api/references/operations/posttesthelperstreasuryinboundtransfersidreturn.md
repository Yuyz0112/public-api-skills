# POST /v1/test_helpers/treasury/inbound_transfers/{id}/return

**Resource:** [test_helpers](../resources/test-helpers.md)
**Test mode: Return an InboundTransfer**
**Operation ID:** `PostTestHelpersTreasuryInboundTransfersIdReturn`

<p>Marks the test mode InboundTransfer object as returned and links the InboundTransfer to a ReceivedDebit. The InboundTransfer must already be in the <code>succeeded</code> state.</p>

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

