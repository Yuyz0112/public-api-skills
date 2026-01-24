# POST /v1/test_helpers/issuing/authorizations/{authorization}/reverse

**Resource:** [test_helpers](../resources/test-helpers.md)
**Reverse a test-mode authorization**
**Operation ID:** `PostTestHelpersIssuingAuthorizationsAuthorizationReverse`

<p>Reverse a test-mode Authorization.</p>

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

