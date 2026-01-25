# PATCH /repos/{owner}/{repo}/code-scanning/alerts/{alert_number}

**Resource:** [code-scanning](../resources/code-scanning.md)
**Update a code scanning alert**
**Operation ID:** `code-scanning/update-alert`

Updates the status of a single code scanning alert.
OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-alert](../schemas/code-scanning-alert/code-scanning-alert.md)

