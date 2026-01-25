# GET /repos/{owner}/{repo}/code-scanning/codeql/databases/{language}

**Resource:** [code-scanning](../resources/code-scanning.md)
**Get a CodeQL database for a repository**
**Operation ID:** `code-scanning/get-codeql-database`

Gets a CodeQL database for a language in a repository.

By default this endpoint returns JSON metadata about the CodeQL database. To
download the CodeQL database binary content, set the `Accept` header of the request
to [`application/zip`](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types), and make sure
your HTTP client is configured to follow redirects or use the `Location` header
to make a second request to get the redirect URL.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `language` | path | string | Yes | The language of the CodeQL database. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 302 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-codeql-database](../schemas/code-scanning-codeql-database/code-scanning-codeql-database.md)

