# GET /v1/identity/verification_sessions/{session}

**Resource:** [identity](../resources/identity.md)
**Retrieve a VerificationSession**
**Operation ID:** `GetIdentityVerificationSessionsSession`

<p>Retrieves the details of a VerificationSession that was previously created.</p>

<p>When the session status is <code>requires_input</code>, you can use this method to retrieve a valid
<code>client_secret</code> or <code>url</code> to allow re-submission.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `session` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[identity.verification_session](../schemas/identity-verification/identity-verification-session.md)

