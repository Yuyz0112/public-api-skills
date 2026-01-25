# TweetTakedownComplianceSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_at` | string (date-time) | Yes | Event time. |
| `quote_tweet_id` | [TweetId](TweetId.md) | No |  |
| `tweet` | object | Yes |  |
| `withheld_in_countries` | CountryCode[] | Yes |  |

## Nested Fields

### `tweet`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author_id` | [UserId](UserId.md) | Yes |  |
| `id` | [TweetId](TweetId.md) | Yes |  |

