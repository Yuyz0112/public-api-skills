# POST /repos/{owner}/{repo}/code-scanning/codeql/variant-analyses

**Resource:** [code-scanning](../resources/code-scanning.md)
**Create a CodeQL variant analysis**
**Operation ID:** `code-scanning/create-variant-analysis`

Creates a new CodeQL variant analysis, which will run a CodeQL query against one or more repositories.

Get started by learning more about [running CodeQL queries at scale with Multi-Repository Variant Analysis](https://docs.github.com/code-security/codeql-for-vs-code/getting-started-with-codeql-for-vs-code/running-codeql-queries-at-scale-with-multi-repository-variant-analysis).

Use the `owner` and `repo` parameters in the URL to specify the controller repository that
will be used for running GitHub Actions workflows and storing the results of the CodeQL variant analysis.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Variant analysis submitted for processing |
| 404 | (reference) |
| 422 | Unable to process variant analysis submission |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-variant-analysis](../schemas/code-scanning-variant-analysis/code-scanning-variant-analysis.md)

