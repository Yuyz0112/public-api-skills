# POST /v1/account_sessions

**Resource:** [account_sessions](../resources/account-sessions.md)
**Create an Account Session**
**Operation ID:** `PostAccountSessions`

<p>Creates a AccountSession object that includes a single-use token that the platform can use on their front-end to grant client-side API access.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[account_session](../schemas/account/account-session.md)

