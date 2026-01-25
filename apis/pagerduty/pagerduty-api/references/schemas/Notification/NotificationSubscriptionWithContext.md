# NotificationSubscriptionWithContext

An object describing the relationship of a NotificationSubscriber and a NotificationSubscribable with additional context on status of subscription attempt.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subscriber_id` | string | No | The ID of the entity being subscribed |
| `subscriber_type` | enum: user, team | No | The type of the entity being subscribed |
| `subscribable_id` | string | No | The ID of the entity being subscribed to |
| `subscribable_type` | enum: incident, business_service | No | The type of the entity being subscribed to |
| `account_id` | string | No | The type of the entity being subscribed to |
| `result` | enum: success, duplicate, unauthorized | No | The resulting status of the subscription |

