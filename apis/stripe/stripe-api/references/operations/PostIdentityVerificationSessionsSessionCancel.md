# POST /v1/identity/verification_sessions/{session}/cancel

**Resource:** [identity](../resources/identity.md)
**Cancel a VerificationSession**
**Operation ID:** `PostIdentityVerificationSessionsSessionCancel`

<p>A VerificationSession object can be canceled when it is in <code>requires_input</code> <a href="/docs/identity/how-sessions-work">status</a>.</p>

<p>Once canceled, future submission attempts are disabled. This cannot be undone. <a href="/docs/identity/verification-sessions#cancel">Learn more</a>.</p>

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

