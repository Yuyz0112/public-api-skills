# POST /v1/terminal/connection_tokens

**Resource:** [terminal](../resources/terminal.md)
**Create a Connection Token**
**Operation ID:** `PostTerminalConnectionTokens`

<p>To connect to a reader the Stripe Terminal SDK needs to retrieve a short-lived connection token from Stripe, proxied through your server. On your backend, add an endpoint that creates and returns a connection token.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.connection_token](../schemas/terminal-connection/terminal-connection-token.md)

