# POST /v1/treasury/inbound_transfers/{inbound_transfer}/cancel

**Resource:** [treasury](../resources/treasury.md)
**Cancel an InboundTransfer**
**Operation ID:** `PostTreasuryInboundTransfersInboundTransferCancel`

<p>Cancels an InboundTransfer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inbound_transfer` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.inbound_transfer](../schemas/treasury-inbound/treasury-inbound-transfer.md)

