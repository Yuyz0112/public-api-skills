# POST /v1/test_helpers/issuing/authorizations

**Resource:** [test_helpers](../resources/test-helpers.md)
**Create a test-mode authorization**
**Operation ID:** `PostTestHelpersIssuingAuthorizations`

<p>Create a test-mode authorization.</p>

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

