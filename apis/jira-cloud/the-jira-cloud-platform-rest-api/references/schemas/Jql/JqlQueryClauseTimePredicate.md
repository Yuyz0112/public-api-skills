# JqlQueryClauseTimePredicate

A time predicate for a temporal JQL clause.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `operand` | [JqlQueryClauseOperand](JqlQueryClauseOperand.md) | Yes |  |
| `operator` | enum: before, after, from... | Yes | The operator between the field and the operand. |

