# GET /repos/{owner}/{repo}/code-scanning/codeql/variant-analyses/{codeql_variant_analysis_id}/repos/{repo_owner}/{repo_name}

**Resource:** [code-scanning](../resources/code-scanning.md)
**Get the analysis status of a repository in a CodeQL variant analysis**
**Operation ID:** `code-scanning/get-variant-analysis-repo-task`

Gets the analysis status of a repository in a CodeQL variant analysis.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo` | path | string | Yes | The name of the controller repository. |
| `codeql_variant_analysis_id` | path | integer | Yes | The ID of the variant analysis. |
| `repo_owner` | path | string | Yes | The account owner of the variant analysis repository. The name is not case sensitive. |
| `repo_name` | path | string | Yes | The name of the variant analysis repository. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-variant-analysis-repo-task](../schemas/code-scanning-variant-analysis-repo-task/code-scanning-variant-analysis-repo-task.md)

