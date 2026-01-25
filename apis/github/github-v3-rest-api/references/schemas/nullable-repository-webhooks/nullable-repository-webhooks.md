# nullable-repository-webhooks

The repository on GitHub where the event occurred. Webhook payloads contain the `repository` property
when the event occurs from activity in a repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier of the repository |
| `node_id` | string | Yes |  |
| `name` | string | Yes | The name of the repository. |
| `full_name` | string | Yes |  |
| `license` | [nullable-license-simple](nullable-license-simple.md) | Yes |  |
| `organization` | [nullable-simple-user](nullable-simple-user.md) | No |  |
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
| `custom_properties` | object | No | The custom properties that were defined for the repository. The keys are the custom property names, and the values are the corresponding custom property values. |
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
| `template_repository` | object | No |  |
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
| `subscribers_count` | integer | No |  |
| `network_count` | integer | No |  |
| `open_issues` | integer | Yes |  |
| `watchers` | integer | Yes |  |
| `master_branch` | string | No |  |
| `starred_at` | string | No |  |
| `anonymous_access_enabled` | boolean | No | Whether anonymous git access is enabled for this repository |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | Yes |  |
| `pull` | boolean | Yes |  |
| `triage` | boolean | No |  |
| `push` | boolean | Yes |  |
| `maintain` | boolean | No |  |

### `template_repository`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `node_id` | string | No |  |
| `name` | string | No |  |
| `full_name` | string | No |  |
| `owner` | object | No |  |
| `private` | boolean | No |  |
| `html_url` | string | No |  |
| `description` | string | No |  |
| `fork` | boolean | No |  |
| `url` | string | No |  |
| `archive_url` | string | No |  |
| `assignees_url` | string | No |  |
| `blobs_url` | string | No |  |
| `branches_url` | string | No |  |
| `collaborators_url` | string | No |  |
| `comments_url` | string | No |  |
| `commits_url` | string | No |  |
| `compare_url` | string | No |  |
| `contents_url` | string | No |  |
| `contributors_url` | string | No |  |
| `deployments_url` | string | No |  |
| `downloads_url` | string | No |  |
| `events_url` | string | No |  |
| `forks_url` | string | No |  |
| `git_commits_url` | string | No |  |
| `git_refs_url` | string | No |  |
| `git_tags_url` | string | No |  |
| `git_url` | string | No |  |
| `issue_comment_url` | string | No |  |
| `issue_events_url` | string | No |  |
| `issues_url` | string | No |  |
| `keys_url` | string | No |  |
| `labels_url` | string | No |  |
| `languages_url` | string | No |  |
| `merges_url` | string | No |  |
| `milestones_url` | string | No |  |
| `notifications_url` | string | No |  |
| `pulls_url` | string | No |  |
| `releases_url` | string | No |  |
| `ssh_url` | string | No |  |
| `stargazers_url` | string | No |  |
| `statuses_url` | string | No |  |
| `subscribers_url` | string | No |  |
| `subscription_url` | string | No |  |
| `tags_url` | string | No |  |
| `teams_url` | string | No |  |
| `trees_url` | string | No |  |
| `clone_url` | string | No |  |
| `mirror_url` | string | No |  |
| `hooks_url` | string | No |  |
| `svn_url` | string | No |  |
| `homepage` | string | No |  |
| `language` | string | No |  |
| `forks_count` | integer | No |  |
| `stargazers_count` | integer | No |  |
| `watchers_count` | integer | No |  |
| `size` | integer | No |  |
| `default_branch` | string | No |  |
| `open_issues_count` | integer | No |  |
| `is_template` | boolean | No |  |
| `topics` | string[] | No |  |
| `has_issues` | boolean | No |  |
| `has_projects` | boolean | No |  |
| `has_wiki` | boolean | No |  |
| `has_pages` | boolean | No |  |
| `has_downloads` | boolean | No |  |
| `archived` | boolean | No |  |
| `disabled` | boolean | No |  |
| `visibility` | string | No |  |
| `pushed_at` | string | No |  |
| `created_at` | string | No |  |
| `updated_at` | string | No |  |
| `permissions` | object | No |  |
| `allow_rebase_merge` | boolean | No |  |
| `temp_clone_token` | string | No |  |
| `allow_squash_merge` | boolean | No |  |
| `allow_auto_merge` | boolean | No |  |
| `delete_branch_on_merge` | boolean | No |  |
| `allow_update_branch` | boolean | No |  |
| `use_squash_pr_title_as_default` | boolean | No |  |
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
| `allow_merge_commit` | boolean | No |  |
| `subscribers_count` | integer | No |  |
| `network_count` | integer | No |  |

#### `template_repository.owner`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | No |  |
| `id` | integer | No |  |
| `node_id` | string | No |  |
| `avatar_url` | string | No |  |
| `gravatar_id` | string | No |  |
| `url` | string | No |  |
| `html_url` | string | No |  |
| `followers_url` | string | No |  |
| `following_url` | string | No |  |
| `gists_url` | string | No |  |
| `starred_url` | string | No |  |
| `subscriptions_url` | string | No |  |
| `organizations_url` | string | No |  |
| `repos_url` | string | No |  |
| `events_url` | string | No |  |
| `received_events_url` | string | No |  |
| `type` | string | No |  |
| `site_admin` | boolean | No |  |

#### `template_repository.permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | No |  |
| `maintain` | boolean | No |  |
| `push` | boolean | No |  |
| `triage` | boolean | No |  |
| `pull` | boolean | No |  |

