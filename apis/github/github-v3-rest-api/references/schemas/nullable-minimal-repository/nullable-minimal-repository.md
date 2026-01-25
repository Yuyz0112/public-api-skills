# nullable-minimal-repository

Minimal Repository

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `name` | string | Yes |  |
| `full_name` | string | Yes |  |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `private` | boolean | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `description` | string | Yes |  |
| `fork` | boolean | Yes |  |
| `url` | string (uri) | Yes |  |
| `archive_url` | string | Yes |  |
| `assignees_url` | string | Yes |  |
| `blobs_url` | string | Yes |  |
| `branches_url` | string | Yes |  |
| `collaborators_url` | string | Yes |  |
| `comments_url` | string | Yes |  |
| `commits_url` | string | Yes |  |
| `compare_url` | string | Yes |  |
| `contents_url` | string | Yes |  |
| `contributors_url` | string (uri) | Yes |  |
| `deployments_url` | string (uri) | Yes |  |
| `downloads_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `git_commits_url` | string | Yes |  |
| `git_refs_url` | string | Yes |  |
| `git_tags_url` | string | Yes |  |
| `git_url` | string | No |  |
| `issue_comment_url` | string | Yes |  |
| `issue_events_url` | string | Yes |  |
| `issues_url` | string | Yes |  |
| `keys_url` | string | Yes |  |
| `labels_url` | string | Yes |  |
| `languages_url` | string (uri) | Yes |  |
| `merges_url` | string (uri) | Yes |  |
| `milestones_url` | string | Yes |  |
| `notifications_url` | string | Yes |  |
| `pulls_url` | string | Yes |  |
| `releases_url` | string | Yes |  |
| `ssh_url` | string | No |  |
| `stargazers_url` | string (uri) | Yes |  |
| `statuses_url` | string | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `trees_url` | string | Yes |  |
| `clone_url` | string | No |  |
| `mirror_url` | string | No |  |
| `hooks_url` | string (uri) | Yes |  |
| `svn_url` | string | No |  |
| `homepage` | string | No |  |
| `language` | string | No |  |
| `forks_count` | integer | No |  |
| `stargazers_count` | integer | No |  |
| `watchers_count` | integer | No |  |
| `size` | integer | No | The size of the repository, in kilobytes. Size is calculated hourly. When a repository is initially created, the size is 0. |
| `default_branch` | string | No |  |
| `open_issues_count` | integer | No |  |
| `is_template` | boolean | No |  |
| `topics` | string[] | No |  |
| `has_issues` | boolean | No |  |
| `has_projects` | boolean | No |  |
| `has_wiki` | boolean | No |  |
| `has_pages` | boolean | No |  |
| `has_downloads` | boolean | No |  |
| `has_discussions` | boolean | No |  |
| `archived` | boolean | No |  |
| `disabled` | boolean | No |  |
| `visibility` | string | No |  |
| `pushed_at` | string (date-time) | No |  |
| `created_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |
| `permissions` | object | No |  |
| `role_name` | string | No |  |
| `temp_clone_token` | string | No |  |
| `delete_branch_on_merge` | boolean | No |  |
| `subscribers_count` | integer | No |  |
| `network_count` | integer | No |  |
| `code_of_conduct` | [code-of-conduct](code-of-conduct.md) | No |  |
| `license` | object | No |  |
| `forks` | integer | No |  |
| `open_issues` | integer | No |  |
| `watchers` | integer | No |  |
| `allow_forking` | boolean | No |  |
| `web_commit_signoff_required` | boolean | No |  |
| `security_and_analysis` | [security-and-analysis](security-and-analysis.md) | No |  |
| `custom_properties` | object | No | The custom properties that were defined for the repository. The keys are the custom property names, and the values are the corresponding custom property values. |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | No |  |
| `maintain` | boolean | No |  |
| `push` | boolean | No |  |
| `triage` | boolean | No |  |
| `pull` | boolean | No |  |

### `license`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | No |  |
| `name` | string | No |  |
| `spdx_id` | string | No |  |
| `url` | string | No |  |
| `node_id` | string | No |  |

