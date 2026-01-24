# POST /v1/topups

**Resource:** [topups](../resources/topups.md)
**Create a top-up**
**Operation ID:** `PostTopups`

<p>Top up the balance of an account</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[topup](../schemas/topup/topup.md)

