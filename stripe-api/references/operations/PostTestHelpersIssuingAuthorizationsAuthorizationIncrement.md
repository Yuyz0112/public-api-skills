# POST /v1/test_helpers/issuing/authorizations/{authorization}/increment

**Resource:** [test_helpers](../resources/test-helpers.md)
**Increment a test-mode authorization**
**Operation ID:** `PostTestHelpersIssuingAuthorizationsAuthorizationIncrement`

<p>Increment a test-mode Authorization.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `authorization` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[issuing.authorization](../schemas/issuing-authorization/issuing-authorization.md)

