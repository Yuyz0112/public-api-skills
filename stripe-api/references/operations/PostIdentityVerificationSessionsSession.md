# POST /v1/identity/verification_sessions/{session}

**Resource:** [identity](../resources/identity.md)
**Update a VerificationSession**
**Operation ID:** `PostIdentityVerificationSessionsSession`

<p>Updates a VerificationSession object.</p>

<p>When the session status is <code>requires_input</code>, you can use this method to update the
verification check and options.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

