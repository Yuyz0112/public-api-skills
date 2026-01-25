# portal_flows_flow_after_completion

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hosted_confirmation` | any | No | Configuration when `after_completion.type=hosted_confirmation`. |
| `redirect` | any | No | Configuration when `after_completion.type=redirect`. |
| `type` | enum: hosted_confirmation, portal_homepage, redirect | Yes | The specified type of behavior after the flow is completed. |

