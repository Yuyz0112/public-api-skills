# JExpEvaluateMetaDataBean

Contains information about the expression evaluation. This bean will be replacing `JiraExpressionEvaluationMetaDataBean` bean as part of new `evaluate` endpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `complexity` | any | No | Contains information about the expression complexity. For example, the number of steps it took to evaluate the expression. |
| `issues` | any | No | Contains information about the `issues` variable in the context. For example, is the issues were loaded with JQL, information about the page will be included here. |

