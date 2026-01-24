# POST /v1/transfers/{transfer}/reversals/{id}

**Resource:** [transfers](../resources/transfers.md)
**Update a reversal**
**Operation ID:** `PostTransfersTransferReversalsId`

<p>Updates the specified reversal by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

<p>This request only accepts metadata and description as arguments.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `transfer` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[transfer_reversal](../schemas/transfer/transfer-reversal.md)

