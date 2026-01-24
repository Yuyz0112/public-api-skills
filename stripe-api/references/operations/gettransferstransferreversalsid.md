# GET /v1/transfers/{transfer}/reversals/{id}

**Resource:** [transfers](../resources/transfers.md)
**Retrieve a reversal**
**Operation ID:** `GetTransfersTransferReversalsId`

<p>By default, you can see the 10 most recent reversals stored directly on the transfer object, but you can also retrieve details about a specific reversal stored on the transfer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

