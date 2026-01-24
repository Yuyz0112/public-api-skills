# POST /v1/test_helpers/issuing/authorizations/{authorization}/capture

**Resource:** [test_helpers](../resources/test-helpers.md)
**Capture a test-mode authorization**
**Operation ID:** `PostTestHelpersIssuingAuthorizationsAuthorizationCapture`

<p>Capture a test-mode authorization.</p>

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

