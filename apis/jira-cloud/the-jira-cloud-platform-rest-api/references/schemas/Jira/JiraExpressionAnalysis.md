# JiraExpressionAnalysis

Details about the analysed Jira expression.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `complexity` | [JiraExpressionComplexity](JiraExpressionComplexity.md) | No |  |
| `errors` | JiraExpressionValidationError[] | No | A list of validation errors. Not included if the expression is valid. |
| `expression` | string | Yes | The analysed expression. |
| `type` | string | No | EXPERIMENTAL. The inferred type of the expression. |
| `valid` | boolean | Yes | Whether the expression is valid and the interpreter will evaluate it. Note that the expression may fail at runtime (for example, if it executes too many expensive operations). |

