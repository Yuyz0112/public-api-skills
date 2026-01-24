# GET /v1/account

**Resource:** [account](../resources/account.md)
**Retrieve account**
**Operation ID:** `GetAccount`

<p>Retrieves the details of an account.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[account](../schemas/account/account.md)

