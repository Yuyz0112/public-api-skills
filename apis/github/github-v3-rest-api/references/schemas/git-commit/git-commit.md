# git-commit

Low-level Git commit operations within a repository

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes | SHA for the commit |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `author` | object | Yes | Identifying information for the git-user |
| `committer` | object | Yes | Identifying information for the git-user |
| `message` | string | Yes | Message describing the purpose of the commit |
| `tree` | object | Yes |  |
| `parents` | object[] | Yes |  |
| `verification` | object | Yes |  |
| `html_url` | string (uri) | Yes |  |

## Nested Fields

### `author`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | Yes | Timestamp of the commit |
| `email` | string | Yes | Git email address of the user |
| `name` | string | Yes | Name of the git user |

### `committer`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | Yes | Timestamp of the commit |
| `email` | string | Yes | Git email address of the user |
| `name` | string | Yes | Name of the git user |

### `tree`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes | SHA for the commit |
| `url` | string (uri) | Yes |  |

### `parents`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes | SHA for the commit |
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |

### `verification`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `verified` | boolean | Yes |  |
| `reason` | string | Yes |  |
| `signature` | string | Yes |  |
| `payload` | string | Yes |  |
| `verified_at` | string | Yes |  |

