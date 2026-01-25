# GET /v1/link_account_sessions/{session}

**Resource:** [link_account_sessions](../resources/link-account-sessions.md)
**Retrieve a Session**
**Operation ID:** `GetLinkAccountSessionsSession`

<p>Retrieves the details of a Financial Connections <code>Session</code></p>

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

[financial_connections.session](../schemas/financial/financial-connections-session.md)

