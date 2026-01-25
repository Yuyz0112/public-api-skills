# webhook-workflow-dispatch

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `inputs` | object | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `ref` | string | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `workflow` | string | Yes |  |

