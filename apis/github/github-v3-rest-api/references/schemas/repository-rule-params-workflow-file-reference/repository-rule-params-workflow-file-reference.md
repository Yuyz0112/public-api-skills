# repository-rule-params-workflow-file-reference

A workflow that must run for this rule to pass

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `path` | string | Yes | The path to the workflow file |
| `ref` | string | No | The ref (branch or tag) of the workflow file to use |
| `repository_id` | integer | Yes | The ID of the repository where the workflow is defined |
| `sha` | string | No | The commit SHA of the workflow file to use |

