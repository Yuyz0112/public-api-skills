# POST /v1/link_account_sessions

**Resource:** [link_account_sessions](../resources/link-account-sessions.md)
**Create a Session**
**Operation ID:** `PostLinkAccountSessions`

<p>To launch the Financial Connections authorization flow, create a <code>Session</code>. The session’s <code>client_secret</code> can be used to launch the flow using Stripe.js.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[financial_connections.session](../schemas/financial/financial-connections-session.md)

