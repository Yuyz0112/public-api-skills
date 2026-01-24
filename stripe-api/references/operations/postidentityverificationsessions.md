# POST /v1/identity/verification_sessions

**Resource:** [identity](../resources/identity.md)
**Create a VerificationSession**
**Operation ID:** `PostIdentityVerificationSessions`

<p>Creates a VerificationSession object.</p>

<p>After the VerificationSession is created, display a verification modal using the session <code>client_secret</code> or send your users to the session’s <code>url</code>.</p>

<p>If your API key is in test mode, verification checks won’t actually process, though everything else will occur as if in live mode.</p>

<p>Related guide: <a href="/docs/identity/verify-identity-documents">Verify your users’ identity documents</a></p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[identity.verification_session](../schemas/identity-verification/identity-verification-session.md)

