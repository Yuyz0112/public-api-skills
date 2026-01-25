# POST /v1/transfers/{id}/reversals

**Resource:** [transfers](../resources/transfers.md)
**Create a transfer reversal**
**Operation ID:** `PostTransfersIdReversals`

<p>When you create a new reversal, you must specify a transfer to create it on.</p>

<p>When reversing transfers, you can optionally reverse part of the transfer. You can do so as many times as you wish until the entire transfer has been reversed.</p>

<p>Once entirely reversed, a transfer can’t be reversed again. This method will return an error when called on an already-reversed transfer, or when trying to reverse more money than is left on a transfer.</p>

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

[transfer_reversal](../schemas/transfer/transfer-reversal.md)

