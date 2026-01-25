# webhook-delete

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pusher_type` | [webhooks_deploy_pusher_type](webhooks-deploy-pusher-type.md) | Yes |  |
| `ref` | [webhooks_ref_0](webhooks-ref-0.md) | Yes |  |
| `ref_type` | enum: tag, branch | Yes | The type of Git ref object deleted in the repository. |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

