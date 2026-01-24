# portal_flows_flow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after_completion` | [portal_flows_flow_after_completion](portal-flows-flow-after-completion.md) | Yes |  |
| `subscription_cancel` | any | No | Configuration when `flow.type=subscription_cancel`. |
| `subscription_update` | any | No | Configuration when `flow.type=subscription_update`. |
| `subscription_update_confirm` | any | No | Configuration when `flow.type=subscription_update_confirm`. |
| `type` | enum: payment_method_update, subscription_cancel, subscription_update... | Yes | Type of flow that the customer will go through. |

