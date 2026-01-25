# JexpEvaluateCtxIssues

The JQL specifying the issues available in the evaluated Jira expression under the `issues` context variable. This bean will be replacing `JexpIssues` bean as part of new `evaluate` endpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `jql` | any | No | The JQL query that specifies the set of issues available in the Jira expression. |

