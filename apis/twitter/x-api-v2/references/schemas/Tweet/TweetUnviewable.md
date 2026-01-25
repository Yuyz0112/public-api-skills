# TweetUnviewable

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | string | Yes | If the label is being applied or removed. Possible values are ‘apply’ or ‘remove’. |
| `event_at` | string (date-time) | Yes | Event time. |
| `tweet` | object | Yes |  |

## Nested Fields

### `tweet`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author_id` | [UserId](UserId.md) | Yes |  |
| `id` | [TweetId](TweetId.md) | Yes |  |

