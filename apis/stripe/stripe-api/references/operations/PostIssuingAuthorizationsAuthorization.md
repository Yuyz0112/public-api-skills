# POST /v1/issuing/authorizations/{authorization}

**Resource:** [issuing](../resources/issuing.md)
**Update an authorization**
**Operation ID:** `PostIssuingAuthorizationsAuthorization`

<p>Updates the specified Issuing <code>Authorization</code> object by setting the values of the parameters passed. Any parameters not provided will be left unchanged.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `authorization` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.authorization](../schemas/issuing-authorization/issuing-authorization.md)

