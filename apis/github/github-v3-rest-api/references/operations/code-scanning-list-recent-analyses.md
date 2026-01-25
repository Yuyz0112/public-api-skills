# GET /repos/{owner}/{repo}/code-scanning/analyses

**Resource:** [code-scanning](../resources/code-scanning.md)
**List code scanning analyses for a repository**
**Operation ID:** `code-scanning/list-recent-analyses`

Lists the details of all code scanning analyses for a repository,
starting with the most recent.
The response is paginated and you can use the `page` and `per_page` parameters
to list the analyses you're interested in.
By default 30 analyses are listed per page.

The `rules_count` field in the response give the number of rules
that were run in the analysis.
For very old analyses this data is not available,
and `0` is returned in this field.

> [!WARNING]
> **Closing down notice:** The `tool_name` field is closing down and will, in future, not be included in the response for this endpoint. The example response reflects this change. The tool name can now be found inside the `tool` field.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | query | code-scanning-ref | No | The Git reference for the analyses you want to list. The `ref` for a branch can be formatted either as `refs/heads/<branch name>` or simply `<branch name>`. To reference a pull request use `refs/pull/<number>/merge`. |
| `sarif_id` | query | code-scanning-analysis-sarif-id | No | Filter analyses belonging to the same SARIF upload. |
| `sort` | query | enum: created | No | The property by which to sort the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [code-scanning-analysis](../schemas/code-scanning-analysis/code-scanning-analysis.md)

