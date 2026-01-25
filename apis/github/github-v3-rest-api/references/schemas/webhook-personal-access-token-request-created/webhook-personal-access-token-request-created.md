# webhook-personal-access-token-request-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | Yes |  |
| `personal_access_token_request` | [personal-access-token-request](personal-access-token-request.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |

