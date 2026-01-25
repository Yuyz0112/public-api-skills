# UserScrubGeoObjectSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_at` | string (date-time) | Yes | Event time. |
| `up_to_tweet_id` | [TweetId](TweetId.md) | Yes |  |
| `user` | object | Yes |  |

## Nested Fields

### `user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [UserId](UserId.md) | Yes |  |

