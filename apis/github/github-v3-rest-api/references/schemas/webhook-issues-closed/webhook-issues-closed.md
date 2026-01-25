# webhook-issues-closed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: closed | Yes | The action that was performed. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `issue` | any | Yes | The [issue](https://docs.github.com/rest/issues/issues#get-an-issue) itself. |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

