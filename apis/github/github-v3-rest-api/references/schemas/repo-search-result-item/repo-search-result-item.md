# repo-search-result-item

Repo Search Result Item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `name` | string | Yes |  |
| `full_name` | string | Yes |  |
| `owner` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `private` | boolean | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `description` | string | Yes |  |
| `fork` | boolean | Yes |  |
| `url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `pushed_at` | string (date-time) | Yes |  |
| `homepage` | string (uri) | Yes |  |
| `size` | integer | Yes |  |
| `stargazers_count` | integer | Yes |  |
| `watchers_count` | integer | Yes |  |
| `language` | string | Yes |  |
| `forks_count` | integer | Yes |  |
| `open_issues_count` | integer | Yes |  |
| `master_branch` | string | No |  |
| `default_branch` | string | Yes |  |
| `score` | number | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `keys_url` | string | Yes |  |
| `collaborators_url` | string | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `hooks_url` | string (uri) | Yes |  |
| `issue_events_url` | string | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `assignees_url` | string | Yes |  |
| `branches_url` | string | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `blobs_url` | string | Yes |  |
| `git_tags_url` | string | Yes |  |
| `git_refs_url` | string | Yes |  |
| `trees_url` | string | Yes |  |
| `statuses_url` | string | Yes |  |
| `languages_url` | string (uri) | Yes |  |
| `stargazers_url` | string (uri) | Yes |  |
| `contributors_url` | string (uri) | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `commits_url` | string | Yes |  |
| `git_commits_url` | string | Yes |  |
| `comments_url` | string | Yes |  |
| `issue_comment_url` | string | Yes |  |
| `contents_url` | string | Yes |  |
| `compare_url` | string | Yes |  |
| `merges_url` | string (uri) | Yes |  |
| `archive_url` | string | Yes |  |
| `downloads_url` | string (uri) | Yes |  |
| `issues_url` | string | Yes |  |
| `pulls_url` | string | Yes |  |
| `milestones_url` | string | Yes |  |
| `notifications_url` | string | Yes |  |
| `labels_url` | string | Yes |  |
| `releases_url` | string | Yes |  |
| `deployments_url` | string (uri) | Yes |  |
| `git_url` | string | Yes |  |
| `ssh_url` | string | Yes |  |
| `clone_url` | string | Yes |  |
| `svn_url` | string (uri) | Yes |  |
| `forks` | integer | Yes |  |
| `open_issues` | integer | Yes |  |
| `watchers` | integer | Yes |  |
| `topics` | string[] | No |  |
| `mirror_url` | string (uri) | Yes |  |
| `has_issues` | boolean | Yes |  |
| `has_projects` | boolean | Yes |  |
| `has_pages` | boolean | Yes |  |
| `has_wiki` | boolean | Yes |  |
| `has_downloads` | boolean | Yes |  |
| `has_discussions` | boolean | No |  |
| `archived` | boolean | Yes |  |
| `disabled` | boolean | Yes | Returns whether or not this repository disabled. |
| `visibility` | string | No | The repository visibility: public, private, or internal. |
| `license` | [nullable-license-simple](nullable-license-simple.md) | Yes |  |
| `permissions` | object | No |  |
| `text_matches` | [search-result-text-matches](search-result-text-matches.md) | No |  |
| `temp_clone_token` | string | No |  |
| `allow_merge_commit` | boolean | No |  |
| `allow_squash_merge` | boolean | No |  |
| `allow_rebase_merge` | boolean | No |  |
| `allow_auto_merge` | boolean | No |  |
| `delete_branch_on_merge` | boolean | No |  |
| `allow_forking` | boolean | No |  |
| `is_template` | boolean | No |  |
| `web_commit_signoff_required` | boolean | No |  |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | Yes |  |
| `maintain` | boolean | No |  |
| `push` | boolean | Yes |  |
| `triage` | boolean | No |  |
| `pull` | boolean | Yes |  |

