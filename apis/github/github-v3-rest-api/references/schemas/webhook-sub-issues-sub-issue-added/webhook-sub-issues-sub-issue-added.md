# webhook-sub-issues-sub-issue-added

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: sub_issue_added | Yes |  |
| `sub_issue_id` | number | Yes | The ID of the sub-issue. |
| `sub_issue` | [issue](issue.md) | Yes |  |
| `sub_issue_repo` | [repository](repository.md) | Yes |  |
| `parent_issue_id` | number | Yes | The ID of the parent issue. |
| `parent_issue` | [issue](issue.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

