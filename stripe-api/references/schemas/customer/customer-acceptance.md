# customer_acceptance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accepted_at` | integer (unix-time) | No | The time that the customer accepts the mandate. |
| `offline` | [offline_acceptance](offline-acceptance.md) | No |  |
| `online` | [online_acceptance](online-acceptance.md) | No |  |
| `type` | enum: offline, online | Yes | The mandate includes the type of customer acceptance information, such as: `online` or `offline`. |

