# Get2TweetsCountsRecentResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | SearchCount[] | No |  |
| `errors` | Problem[] | No |  |
| `meta` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `newest_id` | [NewestId](NewestId.md) | No |  |
| `next_token` | [NextToken](NextToken.md) | No |  |
| `oldest_id` | [OldestId](OldestId.md) | No |  |
| `total_tweet_count` | [Aggregate](Aggregate.md) | No |  |

