# webhook-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | The repository's current description. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `master_branch` | string | Yes | The name of the repository's default branch (usually `main`). |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pusher_type` | [webhooks_deploy_pusher_type](webhooks-deploy-pusher-type.md) | Yes |  |
| `ref` | [webhooks_ref_0](webhooks-ref-0.md) | Yes |  |
| `ref_type` | enum: tag, branch | Yes | The type of Git ref object created in the repository. |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

