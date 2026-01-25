# CompoundClause

A JQL query clause that consists of nested clauses. For example, `(labels in (urgent, blocker) OR lastCommentedBy = currentUser()). Note that, where nesting is not defined, the parser nests JQL clauses based on the operator precedence. For example, "A OR B AND C" is parsed as "(A OR B) AND C". See Setting the precedence of operators for more information about precedence in JQL queries.`

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clauses` | JqlQueryClause[] | Yes | The list of nested clauses. |
| `operator` | enum: and, or, not | Yes | The operator between the clauses. |

