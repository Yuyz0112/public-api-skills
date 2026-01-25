# webhook-personal-access-token-request-denied

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: denied | Yes |  |
| `personal_access_token_request` | [personal-access-token-request](personal-access-token-request.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | Yes |  |

