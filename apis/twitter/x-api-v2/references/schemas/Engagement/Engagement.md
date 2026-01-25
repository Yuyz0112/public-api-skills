# Engagement

An Engagement Api Response.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | No |  |
| `measurement` | object | No |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error` | string | No |  |
| `tweets` | string[] | No |  |

### `measurement`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metrics_time_series` | object[] | No |  |
| `metrics_total` | object[] | No |  |

#### `measurement.metrics_time_series`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tweet_id` | [TweetId](TweetId.md) | No |  |
| `value` | object | No |  |

#### `measurement.metrics_total`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tweet_id` | [TweetId](TweetId.md) | No |  |
| `value` | object[] | No |  |

