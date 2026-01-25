# IssueContextVariable

An [issue](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#issue) specified by ID or key. All the fields of the issue object are available in the Jira expression.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | No | The issue ID. |
| `key` | string | No | The issue key. |
| `type` | string | Yes | Type of custom context variable. |

