# POST /repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/autofix/commits

**Resource:** [code-scanning](../resources/code-scanning.md)
**Commit an autofix for a code scanning alert**
**Operation ID:** `code-scanning/commit-autofix`

Commits an autofix for a code scanning alert.

If an autofix is committed as a result of this request, then this endpoint will return a 201 Created response.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Request Body

**Content Types:** `application/json`

**Schema:** [code-scanning-autofix-commits](../schemas/code-scanning-autofix-commits/code-scanning-autofix-commits.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Unprocessable Entity |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-autofix-commits-response](../schemas/code-scanning-autofix-commits-response/code-scanning-autofix-commits-response.md)

