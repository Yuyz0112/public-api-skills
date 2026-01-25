# UnlikeComplianceSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_at` | string (date-time) | Yes | Event time. |
| `favorite` | object | Yes |  |

## Nested Fields

### `favorite`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [TweetId](TweetId.md) | Yes |  |
| `user_id` | [UserId](UserId.md) | Yes |  |

