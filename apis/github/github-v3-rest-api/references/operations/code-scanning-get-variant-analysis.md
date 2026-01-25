# GET /repos/{owner}/{repo}/code-scanning/codeql/variant-analyses/{codeql_variant_analysis_id}

**Resource:** [code-scanning](../resources/code-scanning.md)
**Get the summary of a CodeQL variant analysis**
**Operation ID:** `code-scanning/get-variant-analysis`

Gets the summary of a CodeQL variant analysis.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `codeql_variant_analysis_id` | path | integer | Yes | The unique identifier of the variant analysis. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-variant-analysis](../schemas/code-scanning-variant-analysis/code-scanning-variant-analysis.md)

