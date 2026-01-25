# POST /v1/treasury/inbound_transfers

**Resource:** [treasury](../resources/treasury.md)
**Create an InboundTransfer**
**Operation ID:** `PostTreasuryInboundTransfers`

<p>Creates an InboundTransfer.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.inbound_transfer](../schemas/treasury-inbound/treasury-inbound-transfer.md)

