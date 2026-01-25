# file-commit

File Commit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content` | object | Yes |  |
| `commit` | object | Yes |  |

## Nested Fields

### `content`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `path` | string | No |  |
| `sha` | string | No |  |
| `size` | integer | No |  |
| `url` | string | No |  |
| `html_url` | string | No |  |
| `git_url` | string | No |  |
| `download_url` | string | No |  |
| `type` | string | No |  |
| `_links` | object | No |  |

#### `content._links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No |  |
| `git` | string | No |  |
| `html` | string | No |  |

### `commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | No |  |
| `node_id` | string | No |  |
| `url` | string | No |  |
| `html_url` | string | No |  |
| `author` | object | No |  |
| `committer` | object | No |  |
| `message` | string | No |  |
| `tree` | object | No |  |
| `parents` | object[] | No |  |
| `verification` | object | No |  |

#### `commit.author`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | No |  |
| `name` | string | No |  |
| `email` | string | No |  |

#### `commit.committer`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | No |  |
| `name` | string | No |  |
| `email` | string | No |  |

#### `commit.tree`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No |  |
| `sha` | string | No |  |

#### `commit.parents`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No |  |
| `html_url` | string | No |  |
| `sha` | string | No |  |

#### `commit.verification`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `verified` | boolean | No |  |
| `reason` | string | No |  |
| `signature` | string | No |  |
| `payload` | string | No |  |
| `verified_at` | string | No |  |

