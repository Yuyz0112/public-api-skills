# POST /v1/transfers/{transfer}

**Resource:** [transfers](../resources/transfers.md)
**Update a transfer**
**Operation ID:** `PostTransfersTransfer`

<p>Updates the specified transfer by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

<p>This request accepts only metadata as an argument.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `transfer` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[transfer](../schemas/transfer/transfer.md)

