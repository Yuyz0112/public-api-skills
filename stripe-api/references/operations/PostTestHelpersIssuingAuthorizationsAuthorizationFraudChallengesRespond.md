# POST /v1/test_helpers/issuing/authorizations/{authorization}/fraud_challenges/respond

**Resource:** [test_helpers](../resources/test-helpers.md)
**Respond to fraud challenge**
**Operation ID:** `PostTestHelpersIssuingAuthorizationsAuthorizationFraudChallengesRespond`

<p>Respond to a fraud challenge on a testmode Issuing authorization, simulating either a confirmation of fraud or a correction of legitimacy.</p>

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

