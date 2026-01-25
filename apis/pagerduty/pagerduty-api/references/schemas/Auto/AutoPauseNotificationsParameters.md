# AutoPauseNotificationsParameters

Defines how alerts on this service are automatically suspended for a period of time before triggering, when identified as likely being transient. Note that automatically pausing notifications is only available on certain plans.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Indicates whether alerts should be automatically suspended when identified as transient |
| `timeout` | enum: 0, 120, 180... | No | Indicates in seconds how long alerts should be suspended before triggering. To automatically select the recommended timeout for a service, set this value to `0`. |
| `recommended_timeout` | enum: 120, 180, 300... | No | The recommended timeout setting for this service based on prior alert patterns. |

