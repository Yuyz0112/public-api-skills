# GET /repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/autofix

**Resource:** [code-scanning](../resources/code-scanning.md)
**Get the status of an autofix for a code scanning alert**
**Operation ID:** `code-scanning/get-autofix`

Gets the status and description of an autofix for a code scanning alert.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-autofix](../schemas/code-scanning-autofix/code-scanning-autofix.md)

