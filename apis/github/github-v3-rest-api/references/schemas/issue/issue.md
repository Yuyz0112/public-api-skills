# issue

Issues are a great way to keep track of tasks, enhancements, and bugs for your projects.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the issue |
| `repository_url` | string (uri) | Yes |  |
| `labels_url` | string | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `number` | integer | Yes | Number uniquely identifying the issue within its repository |
| `state` | string | Yes | State of the issue; either 'open' or 'closed' |
| `state_reason` | enum: completed, reopened, not_planned... | No | The reason for the current state |
| `title` | string | Yes | Title of the issue |
| `body` | string | No | Contents of the issue |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `labels` | any[] | Yes | Labels to associate with this issue; pass one or more label names to replace the set of labels on this issue; send an empty array to clear all labels from the issue; note that the labels are silently dropped for users without push access to the repository |
| `assignee` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `assignees` | simple-user[] | No |  |
| `milestone` | [nullable-milestone](nullable-milestone.md) | Yes |  |
| `locked` | boolean | Yes |  |
| `active_lock_reason` | string | No |  |
| `comments` | integer | Yes |  |
| `pull_request` | object | No |  |
| `closed_at` | string (date-time) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `draft` | boolean | No |  |
| `closed_by` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `body_html` | string | No |  |
| `body_text` | string | No |  |
| `timeline_url` | string (uri) | No |  |
| `type` | [issue-type](issue-type.md) | No |  |
| `repository` | [repository](repository.md) | No |  |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |
| `author_association` | [author-association](author-association.md) | No |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |
| `sub_issues_summary` | [sub-issues-summary](sub-issues-summary.md) | No |  |
| `parent_issue_url` | string (uri) | No | URL to get the parent issue of this issue, if it is a sub-issue |
| `issue_dependencies_summary` | [issue-dependencies-summary](issue-dependencies-summary.md) | No |  |
| `issue_field_values` | issue-field-value[] | No |  |

## Nested Fields

### `pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `merged_at` | string (date-time) | No |  |
| `diff_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `patch_url` | string (uri) | Yes |  |
| `url` | string (uri) | Yes |  |

