# FieldChangedClause

A clause that asserts whether a field was changed. For example, `status CHANGED AFTER startOfMonth(-1M)`.See [CHANGED](https://confluence.atlassian.com/x/dgiiLQ#Advancedsearching-operatorsreference-CHANGEDCHANGED) for more information about the CHANGED operator.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `field` | [JqlQueryField](JqlQueryField.md) | Yes |  |
| `operator` | enum: changed | Yes | The operator applied to the field. |
| `predicates` | JqlQueryClauseTimePredicate[] | Yes | The list of time predicates. |

