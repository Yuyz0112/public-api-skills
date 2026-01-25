# topic-search-result-item

Topic Search Result Item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `display_name` | string | Yes |  |
| `short_description` | string | Yes |  |
| `description` | string | Yes |  |
| `created_by` | string | Yes |  |
| `released` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `featured` | boolean | Yes |  |
| `curated` | boolean | Yes |  |
| `score` | number | Yes |  |
| `repository_count` | integer | No |  |
| `logo_url` | string (uri) | No |  |
| `text_matches` | [search-result-text-matches](search-result-text-matches.md) | No |  |
| `related` | object[] | No |  |
| `aliases` | object[] | No |  |

## Nested Fields

### `related`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topic_relation` | object | No |  |

#### `related.topic_relation`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `name` | string | No |  |
| `topic_id` | integer | No |  |
| `relation_type` | string | No |  |

### `aliases`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topic_relation` | object | No |  |

#### `aliases.topic_relation`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `name` | string | No |  |
| `topic_id` | integer | No |  |
| `relation_type` | string | No |  |

