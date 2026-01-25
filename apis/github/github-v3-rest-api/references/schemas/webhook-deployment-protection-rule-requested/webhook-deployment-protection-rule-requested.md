# webhook-deployment-protection-rule-requested

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: requested | No |  |
| `environment` | string | No | The name of the environment that has the deployment protection rule. |
| `event` | string | No | The event that triggered the deployment protection rule. |
| `deployment_callback_url` | string (uri) | No | The URL to review the deployment protection rule. |
| `deployment` | [deployment](deployment.md) | No |  |
| `pull_requests` | pull-request[] | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

