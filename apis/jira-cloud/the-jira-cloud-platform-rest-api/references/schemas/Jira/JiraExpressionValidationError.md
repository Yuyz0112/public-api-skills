# JiraExpressionValidationError

Details about syntax and type errors. The error details apply to the entire expression, unless the object includes:

 *  `line` and `column`
 *  `expression`

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `column` | integer (int32) | No | The text column in which the error occurred. |
| `expression` | string | No | The part of the expression in which the error occurred. |
| `line` | integer (int32) | No | The text line in which the error occurred. |
| `message` | string | Yes | Details about the error. |
| `type` | enum: syntax, type, other | Yes | The error type. |

