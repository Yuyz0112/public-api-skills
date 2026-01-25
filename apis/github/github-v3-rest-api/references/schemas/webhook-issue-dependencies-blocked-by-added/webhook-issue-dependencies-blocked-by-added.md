# webhook-issue-dependencies-blocked-by-added

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: blocked_by_added | Yes |  |
| `blocked_issue_id` | number | No | The ID of the blocked issue. |
| `blocked_issue` | [issue](issue.md) | No |  |
| `blocking_issue_id` | number | No | The ID of the blocking issue. |
| `blocking_issue` | [issue](issue.md) | No |  |
| `blocking_issue_repo` | [repository](repository.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

