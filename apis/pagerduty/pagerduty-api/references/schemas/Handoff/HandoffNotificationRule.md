# HandoffNotificationRule

A rule for contacting the user for Handoff Notifications.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `notify_advance_in_minutes` | integer | No | The delay before firing the rule, in minutes. |
| `handoff_type` | enum: both, oncall, offcall | Yes | The type of handoff being created. |
| `contact_method` | [ContactMethodReference](ContactMethodReference.md) | Yes |  |

