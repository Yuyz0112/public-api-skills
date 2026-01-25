# repository-rule-commit-author-email-pattern

Parameters to be used for the commit_author_email_pattern rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: commit_author_email_pattern | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | How this rule will appear to users. |
| `negate` | boolean | No | If true, the rule will fail if the pattern matches. |
| `operator` | enum: starts_with, ends_with, contains... | Yes | The operator to use for matching. |
| `pattern` | string | Yes | The pattern to match with. |

