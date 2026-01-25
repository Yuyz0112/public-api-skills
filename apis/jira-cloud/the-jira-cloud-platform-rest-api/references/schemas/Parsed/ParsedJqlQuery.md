# ParsedJqlQuery

Details of a parsed JQL query.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | string[] | No | The list of syntax or validation errors. |
| `query` | string | Yes | The JQL query that was parsed and validated. |
| `structure` | any | No | The syntax tree of the query. Empty if the query was invalid. |
| `warnings` | string[] | No | The list of warning messages |

