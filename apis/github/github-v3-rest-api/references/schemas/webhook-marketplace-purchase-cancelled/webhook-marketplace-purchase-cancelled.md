# webhook-marketplace-purchase-cancelled

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: cancelled | Yes |  |
| `effective_date` | string | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `marketplace_purchase` | [webhooks_marketplace_purchase](webhooks-marketplace-purchase.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `previous_marketplace_purchase` | [webhooks_previous_marketplace_purchase](webhooks-previous-marketplace-purchase.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

