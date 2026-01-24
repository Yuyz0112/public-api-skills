# POST /v1/test_helpers/issuing/authorizations/{authorization}/finalize_amount

**Resource:** [test_helpers](../resources/test-helpers.md)
**Finalize a test-mode authorization's amount**
**Operation ID:** `PostTestHelpersIssuingAuthorizationsAuthorizationFinalizeAmount`

<p>Finalize the amount on an Authorization prior to capture, when the initial authorization was for an estimated amount.</p>

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

