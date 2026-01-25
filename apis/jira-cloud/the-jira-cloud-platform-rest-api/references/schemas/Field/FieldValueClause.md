# FieldValueClause

A clause that asserts the current value of a field. For example, `summary ~ test`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `field` | [JqlQueryField](JqlQueryField.md) | Yes |  |
| `operand` | [JqlQueryClauseOperand](JqlQueryClauseOperand.md) | Yes |  |
| `operator` | enum: =, !=, >... | Yes | The operator between the field and operand. |

