# get-budget

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | ID of the budget. |
| `budget_scope` | enum: enterprise, organization, repository... | Yes | The type of scope for the budget |
| `budget_entity_name` | string | Yes | The name of the entity to apply the budget to |
| `budget_amount` | integer | Yes | The budget amount in whole dollars. For license-based products, this represents the number of licenses. |
| `prevent_further_usage` | boolean | Yes | Whether to prevent additional spending once the budget is exceeded |
| `budget_product_sku` | string | Yes | A single product or sku to apply the budget to. |
| `budget_type` | enum: ProductPricing, SkuPricing | Yes | The type of pricing for the budget |
| `budget_alerting` | object | Yes |  |

## Nested Fields

### `budget_alerting`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `will_alert` | boolean | No | Whether alerts are enabled for this budget |
| `alert_recipients` | string[] | No | Array of user login names who will receive alerts |

