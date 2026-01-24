# GET /v1/treasury/inbound_transfers/{id}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve an InboundTransfer**
**Operation ID:** `GetTreasuryInboundTransfersId`

<p>Retrieves the details of an existing InboundTransfer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

