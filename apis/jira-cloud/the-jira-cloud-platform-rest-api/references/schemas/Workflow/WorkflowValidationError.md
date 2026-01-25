# WorkflowValidationError

The details about a workflow validation error.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | string | No | An error code. |
| `elementReference` | [WorkflowElementReference](WorkflowElementReference.md) | No |  |
| `level` | enum: WARNING, ERROR | No | The validation error level. |
| `message` | string | No | An error message. |
| `type` | enum: RULE, STATUS, STATUS_LAYOUT... | No | The type of element the error or warning references. |

