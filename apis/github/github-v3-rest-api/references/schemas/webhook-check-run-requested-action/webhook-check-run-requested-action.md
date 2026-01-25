# webhook-check-run-requested-action

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: requested_action | Yes |  |
| `check_run` | [check-run-with-simple-check-suite](check-run-with-simple-check-suite.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `requested_action` | object | No | The action requested by the user. |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `requested_action`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `identifier` | string | No | The integrator reference of the action requested by the user. |

