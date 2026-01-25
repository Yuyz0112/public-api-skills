# webhook-check-run-rerequested

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: rerequested | No |  |
| `check_run` | [check-run-with-simple-check-suite](check-run-with-simple-check-suite.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

