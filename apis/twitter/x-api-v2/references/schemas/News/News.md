# News

An AI generated news story.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `category` | string | No | The news category. |
| `cluster_posts_results` | object[] | No |  |
| `contexts` | object | No |  |
| `disclaimer` | string | No |  |
| `hook` | string | No | The news hook. |
| `keywords` | string[] | No |  |
| `last_updated_at_ms` | string (date-time) | No |  |
| `name` | string | No | The headline. |
| `rest_id` | [NewsId](NewsId.md) | Yes |  |
| `summary` | string | No | The news summary. |

## Nested Fields

### `cluster_posts_results`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `post_id` | [TweetId](TweetId.md) | No |  |

### `contexts`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entities` | object | No |  |
| `finance` | object | No |  |
| `sports` | object | No |  |
| `topics` | string[] | No |  |

#### `contexts.entities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `events` | string[] | No |  |
| `organizations` | string[] | No |  |
| `people` | string[] | No |  |
| `places` | string[] | No |  |
| `products` | string[] | No |  |

#### `contexts.finance`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tickers` | string[] | No |  |

#### `contexts.sports`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `teams` | string[] | No |  |

