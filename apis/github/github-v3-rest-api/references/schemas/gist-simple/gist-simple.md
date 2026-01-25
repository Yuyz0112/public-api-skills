# gist-simple

Gist Simple

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `forks` | object[] | No |  |
| `history` | gist-history[] | No |  |
| `fork_of` | object | No | Gist |
| `url` | string | No |  |
| `forks_url` | string | No |  |
| `commits_url` | string | No |  |
| `id` | string | No |  |
| `node_id` | string | No |  |
| `git_pull_url` | string | No |  |
| `git_push_url` | string | No |  |
| `html_url` | string | No |  |
| `files` | object | No |  |
| `public` | boolean | No |  |
| `created_at` | string | No |  |
| `updated_at` | string | No |  |
| `description` | string | No |  |
| `comments` | integer | No |  |
| `comments_enabled` | boolean | No |  |
| `user` | string | No |  |
| `comments_url` | string | No |  |
| `owner` | [simple-user](simple-user.md) | No |  |
| `truncated` | boolean | No |  |

## Nested Fields

### `forks`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `url` | string (uri) | No |  |
| `user` | [public-user](public-user.md) | No |  |
| `created_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |

### `fork_of`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `commits_url` | string (uri) | Yes |  |
| `id` | string | Yes |  |
| `node_id` | string | Yes |  |
| `git_pull_url` | string (uri) | Yes |  |
| `git_push_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `files` | object | Yes |  |
| `public` | boolean | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `description` | string | Yes |  |
| `comments` | integer | Yes |  |
| `comments_enabled` | boolean | No |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `owner` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `truncated` | boolean | No |  |
| `forks` | any[] | No |  |
| `history` | any[] | No |  |

