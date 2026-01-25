# JiraExpressionEvaluateRequestBean

The request to evaluate a Jira expression. This bean will be replacing `JiraExpressionEvaluateRequest` as part of new `evaluate` endpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `context` | any | No | The context in which the Jira expression is evaluated. |
| `expression` | string | Yes | The Jira expression to evaluate. |

