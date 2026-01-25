# webhook-issues-typed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: typed | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `issue` | [webhooks_issue](webhooks-issue.md) | Yes |  |
| `type` | [issue-type](issue-type.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

