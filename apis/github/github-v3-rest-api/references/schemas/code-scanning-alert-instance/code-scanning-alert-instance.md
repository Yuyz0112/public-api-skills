# code-scanning-alert-instance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref` | [code-scanning-ref](code-scanning-ref.md) | No |  |
| `analysis_key` | [code-scanning-analysis-analysis-key](code-scanning-analysis-analysis-key.md) | No |  |
| `environment` | [code-scanning-alert-environment](code-scanning-alert-environment.md) | No |  |
| `category` | [code-scanning-analysis-category](code-scanning-analysis-category.md) | No |  |
| `state` | [code-scanning-alert-state](code-scanning-alert-state.md) | No |  |
| `commit_sha` | string | No |  |
| `message` | object | No |  |
| `location` | [code-scanning-alert-location](code-scanning-alert-location.md) | No |  |
| `html_url` | string | No |  |
| `classifications` | code-scanning-alert-classification[] | No | Classifications that have been applied to the file that triggered the alert.
For example identifying it as documentation, or a generated file. |

## Nested Fields

### `message`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `text` | string | No |  |

