# nullable-repository

A repository on GitHub.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier of the repository |
| `node_id` | string | Yes |  |
| `name` | string | Yes | The name of the repository. |
| `full_name` | string | Yes |  |
| `license` | [nullable-license-simple](nullable-license-simple.md) | Yes |  |
| `forks` | integer | Yes |  |
| `permissions` | object | No |  |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `private` | boolean | Yes | Whether the repository is private or public. |
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
| `git_url` | string | Yes |  |
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
| `ssh_url` | string | Yes |  |
| `stargazers_url` | string (uri) | Yes |  |
| `statuses_url` | string | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `trees_url` | string | Yes |  |
| `clone_url` | string | Yes |  |
| `mirror_url` | string (uri) | Yes |  |
| `hooks_url` | string (uri) | Yes |  |
| `svn_url` | string (uri) | Yes |  |
| `homepage` | string (uri) | Yes |  |
| `language` | string | Yes |  |
| `forks_count` | integer | Yes |  |
| `stargazers_count` | integer | Yes |  |
| `watchers_count` | integer | Yes |  |
| `size` | integer | Yes | The size of the repository, in kilobytes. Size is calculated hourly. When a repository is initially created, the size is 0. |
| `default_branch` | string | Yes | The default branch of the repository. |
| `open_issues_count` | integer | Yes |  |
| `is_template` | boolean | No | Whether this repository acts as a template that can be used to generate new repositories. |
| `topics` | string[] | No |  |
| `has_issues` | boolean | Yes | Whether issues are enabled. |
| `has_projects` | boolean | Yes | Whether projects are enabled. |
| `has_wiki` | boolean | Yes | Whether the wiki is enabled. |
| `has_pages` | boolean | Yes |  |
| `has_downloads` | boolean | Yes | Whether downloads are enabled. |
| `has_discussions` | boolean | No | Whether discussions are enabled. |
| `archived` | boolean | Yes | Whether the repository is archived. |
| `disabled` | boolean | Yes | Returns whether or not this repository disabled. |
| `visibility` | string | No | The repository visibility: public, private, or internal. |
| `pushed_at` | string (date-time) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `allow_rebase_merge` | boolean | No | Whether to allow rebase merges for pull requests. |
| `temp_clone_token` | string | No |  |
| `allow_squash_merge` | boolean | No | Whether to allow squash merges for pull requests. |
| `allow_auto_merge` | boolean | No | Whether to allow Auto-merge to be used on pull requests. |
| `delete_branch_on_merge` | boolean | No | Whether to delete head branches when pull requests are merged |
| `allow_update_branch` | boolean | No | Whether or not a pull request head branch that is behind its base branch can always be updated even if it is not required to be up to date before merging. |
| `use_squash_pr_title_as_default` | boolean | No | Whether a squash merge commit can use the pull request title as default. **This property is closing down. Please use `squash_merge_commit_title` instead. |
| `squash_merge_commit_title` | enum: PR_TITLE, COMMIT_OR_PR_TITLE | No | The default value for a squash merge commit title:

- `PR_TITLE` - default to the pull request's title.
- `COMMIT_OR_PR_TITLE` - default to the commit's title (if only one commit) or the pull request's title (when more than one commit). |
| `squash_merge_commit_message` | enum: PR_BODY, COMMIT_MESSAGES, BLANK | No | The default value for a squash merge commit message:

- `PR_BODY` - default to the pull request's body.
- `COMMIT_MESSAGES` - default to the branch's commit messages.
- `BLANK` - default to a blank commit message. |
| `merge_commit_title` | enum: PR_TITLE, MERGE_MESSAGE | No | The default value for a merge commit title.

- `PR_TITLE` - default to the pull request's title.
- `MERGE_MESSAGE` - default to the classic title for a merge message (e.g., Merge pull request #123 from branch-name). |
| `merge_commit_message` | enum: PR_BODY, PR_TITLE, BLANK | No | The default value for a merge commit message.

- `PR_TITLE` - default to the pull request's title.
- `PR_BODY` - default to the pull request's body.
- `BLANK` - default to a blank commit message. |
| `allow_merge_commit` | boolean | No | Whether to allow merge commits for pull requests. |
| `allow_forking` | boolean | No | Whether to allow forking this repo |
| `web_commit_signoff_required` | boolean | No | Whether to require contributors to sign off on web-based commits |
| `open_issues` | integer | Yes |  |
| `watchers` | integer | Yes |  |
| `master_branch` | string | No |  |
| `starred_at` | string | No |  |
| `anonymous_access_enabled` | boolean | No | Whether anonymous git access is enabled for this repository |
| `code_search_index_status` | object | No | The status of the code search index for this repository |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | Yes |  |
| `pull` | boolean | Yes |  |
| `triage` | boolean | No |  |
| `push` | boolean | Yes |  |
| `maintain` | boolean | No |  |

### `code_search_index_status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `lexical_search_ok` | boolean | No |  |
| `lexical_commit_sha` | string | No |  |

