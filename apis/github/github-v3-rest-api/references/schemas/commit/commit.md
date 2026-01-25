# commit

Commit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `sha` | string | Yes |  |
| `node_id` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `commit` | object | Yes |  |
| `author` | any | Yes |  |
| `committer` | any | Yes |  |
| `parents` | object[] | Yes |  |
| `stats` | object | No |  |
| `files` | diff-entry[] | No |  |

## Nested Fields

### `commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `author` | [nullable-git-user](nullable-git-user.md) | Yes |  |
| `committer` | [nullable-git-user](nullable-git-user.md) | Yes |  |
| `message` | string | Yes |  |
| `comment_count` | integer | Yes |  |
| `tree` | object | Yes |  |
| `verification` | [verification](verification.md) | No |  |

#### `commit.tree`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |

### `parents`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | No |  |

### `stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additions` | integer | No |  |
| `deletions` | integer | No |  |
| `total` | integer | No |  |

