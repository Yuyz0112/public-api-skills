# FieldWasClause

A clause that asserts a previous value of a field. For example, `status WAS "Resolved" BY currentUser() BEFORE "2019/02/02"`. See [WAS](https://confluence.atlassian.com/x/dgiiLQ#Advancedsearching-operatorsreference-WASWAS) for more information about the WAS operator.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `field` | [JqlQueryField](JqlQueryField.md) | Yes |  |
| `operand` | [JqlQueryClauseOperand](JqlQueryClauseOperand.md) | Yes |  |
| `operator` | enum: was, was in, was not in... | Yes | The operator between the field and operand. |
| `predicates` | JqlQueryClauseTimePredicate[] | Yes | The list of time predicates. |

