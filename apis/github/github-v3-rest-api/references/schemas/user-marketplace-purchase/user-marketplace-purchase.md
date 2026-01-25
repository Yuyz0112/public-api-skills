# user-marketplace-purchase

User Marketplace Purchase

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_cycle` | string | Yes |  |
| `next_billing_date` | string (date-time) | Yes |  |
| `unit_count` | integer | Yes |  |
| `on_free_trial` | boolean | Yes |  |
| `free_trial_ends_on` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `account` | [marketplace-account](marketplace-account.md) | Yes |  |
| `plan` | [marketplace-listing-plan](marketplace-listing-plan.md) | Yes |  |

