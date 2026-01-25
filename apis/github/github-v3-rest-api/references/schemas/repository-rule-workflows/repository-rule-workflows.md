# repository-rule-workflows

Require all changes made to a targeted branch to pass the specified workflows before they can be merged.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: workflows | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `do_not_enforce_on_create` | boolean | No | Allow repositories and branches to be created if a check would otherwise prohibit it. |
| `workflows` | repository-rule-params-workflow-file-reference[] | Yes | Workflows that must pass for this rule to pass. |

