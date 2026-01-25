# WorkflowStatus

Details of a workflow status.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the issue status. |
| `name` | string | Yes | The name of the status in the workflow. |
| `properties` | object | No | Additional properties that modify the behavior of issues in this status. Supports the properties `jira.issue.editable` and `issueEditable` (deprecated) that indicate whether issues are editable. |

