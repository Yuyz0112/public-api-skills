# GET /repos/{owner}/{repo}/code-scanning/codeql/databases

**Resource:** [code-scanning](../resources/code-scanning.md)
**List CodeQL databases for a repository**
**Operation ID:** `code-scanning/list-codeql-databases`

Lists the CodeQL databases that are available in a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [code-scanning-codeql-database](../schemas/code-scanning-codeql-database/code-scanning-codeql-database.md)

