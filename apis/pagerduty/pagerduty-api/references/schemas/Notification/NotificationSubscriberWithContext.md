# NotificationSubscriberWithContext

A reference of a subscriber entity with additional subscription context.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subscriber_id` | string | No | The ID of the entity being subscribed |
| `subscriber_type` | enum: user, team | No | The type of the entity being subscribed |
| `has_indirect_subscription` | boolean | No | If this subcriber has an indirect subscription to this incident via another object |
| `subscribed_via` | object[] | No |  |

## Nested Fields

### `subscribed_via`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The id of the object this subscriber is subscribed via |
| `name` | string | No | The type of the object this subscriber is subscribed via |

