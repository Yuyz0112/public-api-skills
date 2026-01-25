# issue-search-result-item

Issue Search Result Item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `repository_url` | string (uri) | Yes |  |
| `labels_url` | string | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `title` | string | Yes |  |
| `locked` | boolean | Yes |  |
| `active_lock_reason` | string | No |  |
| `assignees` | simple-user[] | No |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `labels` | object[] | Yes |  |
| `sub_issues_summary` | [sub-issues-summary](sub-issues-summary.md) | No |  |
| `issue_dependencies_summary` | [issue-dependencies-summary](issue-dependencies-summary.md) | No |  |
| `issue_field_values` | issue-field-value[] | No |  |
| `state` | string | Yes |  |
| `state_reason` | string | No |  |
| `assignee` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `milestone` | [nullable-milestone](nullable-milestone.md) | Yes |  |
| `comments` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `closed_at` | string (date-time) | Yes |  |
| `text_matches` | [search-result-text-matches](search-result-text-matches.md) | No |  |
| `pull_request` | object | No |  |
| `body` | string | No |  |
| `score` | number | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `draft` | boolean | No |  |
| `repository` | [repository](repository.md) | No |  |
| `body_html` | string | No |  |
| `body_text` | string | No |  |
| `timeline_url` | string (uri) | No |  |
| `type` | [issue-type](issue-type.md) | No |  |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |

## Nested Fields

### `labels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | No |  |
| `node_id` | string | No |  |
| `url` | string | No |  |
| `name` | string | No |  |
| `color` | string | No |  |
| `default` | boolean | No |  |
| `description` | string | No |  |

### `pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `merged_at` | string (date-time) | No |  |
| `diff_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `patch_url` | string (uri) | Yes |  |
| `url` | string (uri) | Yes |  |

