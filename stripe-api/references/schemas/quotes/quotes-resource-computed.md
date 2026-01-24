# quotes_resource_computed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `recurring` | any | No | The definitive totals and line items the customer will be charged on a recurring basis. Takes into account the line items with recurring prices and discounts with `duration=forever` coupons only. Defaults to `null` if no inputted line items with recurring prices. |
| `upfront` | [quotes_resource_upfront](quotes-resource-upfront.md) | Yes |  |

