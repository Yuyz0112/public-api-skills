# GET /repos/{owner}/{repo}/dependency-graph/compare/{basehead}

**Resource:** [dependency-graph](../resources/dependency-graph.md)
**Get a diff of the dependencies between commits**
**Operation ID:** `dependency-graph/diff-range`

Gets the diff of the dependency changes between two commits of a repository, based on the changes to the dependency manifests made in those commits.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `basehead` | path | string | Yes | The base and head Git revisions to compare. The Git revisions will be resolved to commit SHAs. Named revisions will be resolved to their corresponding HEAD commits, and an appropriate merge base will be determined. This parameter expects the format `{base}...{head}`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dependency-graph-diff](../schemas/dependency-graph-diff/dependency-graph-diff.md)

