# POST /v1/treasury/outbound_transfers

**Resource:** [treasury](../resources/treasury.md)
**Create an OutboundTransfer**
**Operation ID:** `PostTreasuryOutboundTransfers`

<p>Creates an OutboundTransfer.</p>

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

