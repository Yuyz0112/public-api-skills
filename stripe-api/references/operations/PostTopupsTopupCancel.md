# POST /v1/topups/{topup}/cancel

**Resource:** [topups](../resources/topups.md)
**Cancel a top-up**
**Operation ID:** `PostTopupsTopupCancel`

<p>Cancels a top-up. Only pending top-ups can be canceled.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `topup` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[topup](../schemas/topup/topup.md)

