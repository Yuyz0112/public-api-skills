# marketplace-purchase

Marketplace Purchase

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | Yes |  |
| `type` | string | Yes |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `organization_billing_email` | string | No |  |
| `email` | string | No |  |
| `marketplace_pending_change` | object | No |  |
| `marketplace_purchase` | object | Yes |  |

## Nested Fields

### `marketplace_pending_change`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `is_installed` | boolean | No |  |
| `effective_date` | string | No |  |
| `unit_count` | integer | No |  |
| `id` | integer | No |  |
| `plan` | [marketplace-listing-plan](marketplace-listing-plan.md) | No |  |

### `marketplace_purchase`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_cycle` | string | No |  |
| `next_billing_date` | string | No |  |
| `is_installed` | boolean | No |  |
| `unit_count` | integer | No |  |
| `on_free_trial` | boolean | No |  |
| `free_trial_ends_on` | string | No |  |
| `updated_at` | string | No |  |
| `plan` | [marketplace-listing-plan](marketplace-listing-plan.md) | No |  |

