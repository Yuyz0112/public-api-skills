# webhooks_previous_marketplace_purchase

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | object | Yes |  |
| `billing_cycle` | string | Yes |  |
| `free_trial_ends_on` | any | Yes |  |
| `next_billing_date` | string | No |  |
| `on_free_trial` | boolean | Yes |  |
| `plan` | object | Yes |  |
| `unit_count` | integer | Yes |  |

## Nested Fields

### `account`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `node_id` | string | Yes |  |
| `organization_billing_email` | string | Yes |  |
| `type` | string | Yes |  |

### `plan`

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

