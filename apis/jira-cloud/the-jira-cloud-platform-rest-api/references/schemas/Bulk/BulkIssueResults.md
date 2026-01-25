# BulkIssueResults

The list of requested issues & fields.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueErrors` | IssueError[] | No | When Jira can't return an issue enumerated in a request due to a retriable error or payload constraint, we'll return the respective issue ID with a corresponding error message. This list is empty when there are no errors Issues which aren't found or that the user doesn't have permission to view won't be returned in this list. |
| `issues` | IssueBean[] | No | The list of issues. |

