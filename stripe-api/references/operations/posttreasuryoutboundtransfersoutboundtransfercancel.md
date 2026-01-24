# POST /v1/treasury/outbound_transfers/{outbound_transfer}/cancel

**Resource:** [treasury](../resources/treasury.md)
**Cancel an OutboundTransfer**
**Operation ID:** `PostTreasuryOutboundTransfersOutboundTransferCancel`

<p>An OutboundTransfer can be canceled if the funds have not yet been paid out.</p>

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

