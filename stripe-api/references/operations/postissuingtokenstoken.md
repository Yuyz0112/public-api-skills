# POST /v1/issuing/tokens/{token}

**Resource:** [issuing](../resources/issuing.md)
**Update a token status**
**Operation ID:** `PostIssuingTokensToken`

<p>Attempts to update the specified Issuing <code>Token</code> object to the status specified.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.token](../schemas/issuing-token/issuing-token.md)

