# webhook-marketplace-purchase-changed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: changed | Yes |  |
| `effective_date` | string | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `marketplace_purchase` | [webhooks_marketplace_purchase](webhooks-marketplace-purchase.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `previous_marketplace_purchase` | object | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `previous_marketplace_purchase`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | object | Yes |  |
| `billing_cycle` | string | Yes |  |
| `free_trial_ends_on` | string | Yes |  |
| `next_billing_date` | string | No |  |
| `on_free_trial` | boolean | Yes |  |
| `plan` | object | Yes |  |
| `unit_count` | integer | Yes |  |

#### `previous_marketplace_purchase.account`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `node_id` | string | Yes |  |
| `organization_billing_email` | string | Yes |  |
| `type` | string | Yes |  |

#### `previous_marketplace_purchase.plan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bullets` | string[] | Yes |  |
| `description` | string | Yes |  |
| `has_free_trial` | boolean | Yes |  |
| `id` | integer | Yes |  |
| `monthly_price_in_cents` | integer | Yes |  |
| `name` | string | Yes |  |
| `price_model` | enum: FREE, FLAT_RATE, PER_UNIT | Yes |  |
| `unit_name` | string | Yes |  |
| `yearly_price_in_cents` | integer | Yes |  |

