# GET /v1/issuing/tokens/{token}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve an issuing token**
**Operation ID:** `GetIssuingTokensToken`

<p>Retrieves an Issuing <code>Token</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `token` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.token](../schemas/issuing-token/issuing-token.md)

