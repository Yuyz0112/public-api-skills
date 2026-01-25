# GET /repos/{owner}/{repo}/code-scanning/sarifs/{sarif_id}

**Resource:** [code-scanning](../resources/code-scanning.md)
**Get information about a SARIF upload**
**Operation ID:** `code-scanning/get-sarif`

Gets information about a SARIF upload, including the status and the URL of the analysis that was uploaded so that you can retrieve details of the analysis. For more information, see "[Get a code scanning analysis for a repository](/rest/code-scanning/code-scanning#get-a-code-scanning-analysis-for-a-repository)."
OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sarif_id` | path | string | Yes | The SARIF ID obtained after uploading. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | Not Found if the sarif id does not match any upload |
| 503 | (reference) |

**Success Response Schema:**

[code-scanning-sarifs-status](../schemas/code-scanning-sarifs-status/code-scanning-sarifs-status.md)

