# POST /repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/autofix

**Resource:** [code-scanning](../resources/code-scanning.md)
**Create an autofix for a code scanning alert**
**Operation ID:** `code-scanning/create-autofix`

Creates an autofix for a code scanning alert.

If a new autofix is to be created as a result of this request or is currently being generated, then this endpoint will return a 202 Accepted response.

If an autofix already exists for a given alert, then this endpoint will return a 200 OK response.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 202 | Accepted |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Unprocessable Entity |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-autofix](../schemas/code-scanning-autofix/code-scanning-autofix.md)

