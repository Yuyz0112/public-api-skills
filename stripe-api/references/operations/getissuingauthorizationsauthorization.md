# GET /v1/issuing/authorizations/{authorization}

**Resource:** [issuing](../resources/issuing.md)
**Retrieve an authorization**
**Operation ID:** `GetIssuingAuthorizationsAuthorization`

<p>Retrieves an Issuing <code>Authorization</code> object.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `authorization` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.authorization](../schemas/issuing-authorization/issuing-authorization.md)

