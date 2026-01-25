# TweetEditComplianceObjectSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `edit_tweet_ids` | TweetId[] | Yes |  |
| `event_at` | string (date-time) | Yes | Event time. |
| `initial_tweet_id` | [TweetId](TweetId.md) | Yes |  |
| `tweet` | object | Yes |  |

## Nested Fields

### `tweet`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [TweetId](TweetId.md) | Yes |  |

