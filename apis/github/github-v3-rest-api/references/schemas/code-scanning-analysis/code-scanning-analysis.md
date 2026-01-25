# code-scanning-analysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref` | [code-scanning-ref](code-scanning-ref.md) | Yes |  |
| `commit_sha` | [code-scanning-analysis-commit-sha](code-scanning-analysis-commit-sha.md) | Yes |  |
| `analysis_key` | [code-scanning-analysis-analysis-key](code-scanning-analysis-analysis-key.md) | Yes |  |
| `environment` | [code-scanning-analysis-environment](code-scanning-analysis-environment.md) | Yes |  |
| `category` | [code-scanning-analysis-category](code-scanning-analysis-category.md) | No |  |
| `error` | string | Yes |  |
| `created_at` | [code-scanning-analysis-created-at](code-scanning-analysis-created-at.md) | Yes |  |
| `results_count` | integer | Yes | The total number of results in the analysis. |
| `rules_count` | integer | Yes | The total number of rules used in the analysis. |
| `id` | integer | Yes | Unique identifier for this analysis. |
| `url` | [code-scanning-analysis-url](code-scanning-analysis-url.md) | Yes |  |
| `sarif_id` | [code-scanning-analysis-sarif-id](code-scanning-analysis-sarif-id.md) | Yes |  |
| `tool` | [code-scanning-analysis-tool](code-scanning-analysis-tool.md) | Yes |  |
| `deletable` | boolean | Yes |  |
| `warning` | string | Yes | Warning generated when processing the analysis |

