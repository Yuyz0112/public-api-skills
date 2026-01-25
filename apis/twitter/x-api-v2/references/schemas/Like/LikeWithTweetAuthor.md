# LikeWithTweetAuthor

A Like event, with the tweet author user and the tweet being liked

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | Creation time of the Tweet. |
| `id` | [LikeId](LikeId.md) | No |  |
| `liked_tweet_id` | [TweetId](TweetId.md) | No |  |
| `timestamp_ms` | integer (int32) | No | Timestamp in milliseconds of creation. |
| `tweet_author_id` | [UserId](UserId.md) | No |  |

