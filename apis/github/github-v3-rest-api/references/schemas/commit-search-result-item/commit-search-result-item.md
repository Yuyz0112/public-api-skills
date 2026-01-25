# commit-search-result-item

Commit Search Result Item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `sha` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `commit` | object | Yes |  |
| `author` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `committer` | [nullable-git-user](nullable-git-user.md) | Yes |  |
| `parents` | object[] | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `score` | number | Yes |  |
| `node_id` | string | Yes |  |
| `text_matches` | [search-result-text-matches](search-result-text-matches.md) | No |  |

## Nested Fields

### `commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | object | Yes |  |
| `committer` | [nullable-git-user](nullable-git-user.md) | Yes |  |
| `comment_count` | integer | Yes |  |
| `message` | string | Yes |  |
| `tree` | object | Yes |  |
| `url` | string (uri) | Yes |  |
| `verification` | [verification](verification.md) | No |  |

#### `commit.author`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `email` | string | Yes |  |
| `date` | string (date-time) | Yes |  |

#### `commit.tree`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |

### `parents`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No |  |
| `html_url` | string | No |  |
| `sha` | string | No |  |

