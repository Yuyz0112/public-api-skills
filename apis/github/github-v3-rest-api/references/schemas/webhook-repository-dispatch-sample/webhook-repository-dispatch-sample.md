# webhook-repository-dispatch-sample

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes | The `event_type` that was specified in the `POST /repos/{owner}/{repo}/dispatches` request body. |
| `branch` | string | Yes |  |
| `client_payload` | object | Yes | The `client_payload` that was specified in the `POST /repos/{owner}/{repo}/dispatches` request body. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

