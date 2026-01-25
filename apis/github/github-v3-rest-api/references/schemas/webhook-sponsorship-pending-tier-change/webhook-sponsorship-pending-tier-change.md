# webhook-sponsorship-pending-tier-change

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: pending_tier_change | Yes |  |
| `changes` | [webhooks_changes_8](webhooks-changes-8.md) | Yes |  |
| `effective_date` | [webhooks_effective_date](webhooks-effective-date.md) | No |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `sponsorship` | [webhooks_sponsorship](webhooks-sponsorship.md) | Yes |  |

