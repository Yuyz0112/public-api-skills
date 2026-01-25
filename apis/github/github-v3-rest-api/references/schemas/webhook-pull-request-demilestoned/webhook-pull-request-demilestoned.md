# webhook-pull-request-demilestoned

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: demilestoned | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `milestone` | [milestone](milestone.md) | No |  |
| `number` | [webhooks_number](webhooks-number.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pull_request` | [webhooks_pull_request_5](webhooks-pull-request-5.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

