# code-scanning-variant-analysis-skipped-repo-group

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository_count` | integer | Yes | The total number of repositories that were skipped for this reason. |
| `repositories` | code-scanning-variant-analysis-repository[] | Yes | A list of repositories that were skipped. This list may not include all repositories that were skipped. This is only available when the repository was found and the user has access to it. |

