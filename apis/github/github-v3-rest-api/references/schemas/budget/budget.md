# budget

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier for the budget |
| `budget_type` | enum: SkuPricing, ProductPricing | Yes | The type of pricing for the budget |
| `budget_amount` | integer | Yes | The budget amount limit in whole dollars. For license-based products, this represents the number of licenses. |
| `prevent_further_usage` | boolean | Yes | The type of limit enforcement for the budget |
| `budget_scope` | string | Yes | The scope of the budget (enterprise, organization, repository, cost center) |
| `budget_entity_name` | string | No | The name of the entity for the budget (enterprise does not require a name). |
| `budget_product_sku` | string | Yes | A single product or sku to apply the budget to. |
| `budget_alerting` | object | Yes |  |

## Nested Fields

### `budget_alerting`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `will_alert` | boolean | Yes | Whether alerts are enabled for this budget |
| `alert_recipients` | string[] | Yes | Array of user login names who will receive alerts |

