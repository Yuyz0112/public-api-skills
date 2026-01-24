# POST /v1/topups/{topup}

**Resource:** [topups](../resources/topups.md)
**Update a top-up**
**Operation ID:** `PostTopupsTopup`

<p>Updates the metadata of a top-up. Other top-up details are not editable by design.</p>

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

