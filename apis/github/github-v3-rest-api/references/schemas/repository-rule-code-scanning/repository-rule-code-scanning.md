# repository-rule-code-scanning

Choose which tools must provide code scanning results before the reference is updated. When configured, code scanning must be enabled and have results for both the commit and the reference being updated.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: code_scanning | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code_scanning_tools` | repository-rule-params-code-scanning-tool[] | Yes | Tools that must provide code scanning results for this rule to pass. |

