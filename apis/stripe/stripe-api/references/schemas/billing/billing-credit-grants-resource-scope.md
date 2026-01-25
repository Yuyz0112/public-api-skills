# billing_credit_grants_resource_scope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `price_type` | enum: metered | No | The price type that credit grants can apply to. We currently only support the `metered` price type. This refers to prices that have a [Billing Meter](https://docs.stripe.com/api/billing/meter) attached to them. Cannot be used in combination with `prices`. |
| `prices` | billing_credit_grants_resource_applicable_price[] | No | The prices that credit grants can apply to. We currently only support `metered` prices. This refers to prices that have a [Billing Meter](https://docs.stripe.com/api/billing/meter) attached to them. Cannot be used in combination with `price_type`. |

