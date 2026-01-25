# recurring

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `interval` | enum: day, month, week... | Yes | The frequency at which a subscription is billed. One of `day`, `week`, `month` or `year`. |
| `interval_count` | integer | Yes | The number of intervals (specified in the `interval` attribute) between subscription billings. For example, `interval=month` and `interval_count=3` bills every 3 months. |
| `meter` | string | No | The meter tracking the usage of a metered price |
| `usage_type` | enum: licensed, metered | Yes | Configures how the quantity per period should be determined. Can be either `metered` or `licensed`. `licensed` automatically bills the `quantity` set when adding it to a subscription. `metered` aggregates the total usage based on usage records. Defaults to `licensed`. |

