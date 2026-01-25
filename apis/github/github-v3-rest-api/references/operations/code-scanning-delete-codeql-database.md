# DELETE /repos/{owner}/{repo}/code-scanning/codeql/databases/{language}

**Resource:** [code-scanning](../resources/code-scanning.md)
**Delete a CodeQL database**
**Operation ID:** `code-scanning/delete-codeql-database`

Deletes a CodeQL database for a language in a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `language` | path | string | Yes | The language of the CodeQL database. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

