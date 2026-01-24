# POST /v1/identity/verification_sessions/{session}/redact

**Resource:** [identity](../resources/identity.md)
**Redact a VerificationSession**
**Operation ID:** `PostIdentityVerificationSessionsSessionRedact`

<p>Redact a VerificationSession to remove all collected information from Stripe. This will redact
the VerificationSession and all objects related to it, including VerificationReports, Events,
request logs, etc.</p>

<p>A VerificationSession object can be redacted when it is in <code>requires_input</code> or <code>verified</code>
<a href="/docs/identity/how-sessions-work">status</a>. Redacting a VerificationSession in <code>requires_action</code>
state will automatically cancel it.</p>

<p>The redaction process may take up to four days. When the redaction process is in progress, the
VerificationSession’s <code>redaction.status</code> field will be set to <code>processing</code>; when the process is
finished, it will change to <code>redacted</code> and an <code>identity.verification_session.redacted</code> event
will be emitted.</p>

<p>Redaction is irreversible. Redacted objects are still accessible in the Stripe API, but all the
fields that contain personal data will be replaced by the string <code>[redacted]</code> or a similar
placeholder. The <code>metadata</code> field will also be erased. Redacted objects cannot be updated or
used for any purpose.</p>

<p><a href="/docs/identity/verification-sessions#redact">Learn more</a>.</p>

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

