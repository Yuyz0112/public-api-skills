# webhooks_pull_request_5

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `_links` | object | Yes |  |
| `active_lock_reason` | enum: resolved, off-topic, too heated... | Yes |  |
| `additions` | integer | No |  |
| `assignee` | object | Yes |  |
| `assignees` | object[] | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `auto_merge` | object | Yes | The status of auto merging a pull request. |
| `base` | object | Yes |  |
| `body` | string | Yes |  |
| `changed_files` | integer | No |  |
| `closed_at` | string (date-time) | Yes |  |
| `comments` | integer | No |  |
| `comments_url` | string (uri) | Yes |  |
| `commits` | integer | No |  |
| `commits_url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `deletions` | integer | No |  |
| `diff_url` | string (uri) | Yes |  |
| `draft` | boolean | Yes | Indicates whether or not the pull request is a draft. |
| `head` | object | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `issue_url` | string (uri) | Yes |  |
| `labels` | object[] | Yes |  |
| `locked` | boolean | Yes |  |
| `maintainer_can_modify` | boolean | No | Indicates whether maintainers can modify the pull request. |
| `merge_commit_sha` | string | Yes |  |
| `mergeable` | boolean | No |  |
| `mergeable_state` | string | No |  |
| `merged` | boolean | No |  |
| `merged_at` | string (date-time) | Yes |  |
| `merged_by` | object | No |  |
| `milestone` | object | Yes | A collection of related issues and pull requests. |
| `node_id` | string | Yes |  |
| `number` | integer | Yes | Number uniquely identifying the pull request within its repository. |
| `patch_url` | string (uri) | Yes |  |
| `rebaseable` | boolean | No |  |
| `requested_reviewers` | any[] | Yes |  |
| `requested_teams` | object[] | Yes |  |
| `review_comment_url` | string (uri-template) | Yes |  |
| `review_comments` | integer | No |  |
| `review_comments_url` | string (uri) | Yes |  |
| `state` | enum: open, closed | Yes | State of this Pull Request. Either `open` or `closed`. |
| `statuses_url` | string (uri) | Yes |  |
| `title` | string | Yes | The title of the pull request. |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |
| `user` | object | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comments` | object | Yes |  |
| `commits` | object | Yes |  |
| `html` | object | Yes |  |
| `issue` | object | Yes |  |
| `review_comment` | object | Yes |  |
| `review_comments` | object | Yes |  |
| `self` | object | Yes |  |
| `statuses` | object | Yes |  |

#### `_links.comments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.commits`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.html`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.issue`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.review_comment`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.review_comments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.self`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.statuses`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

### `assignee`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization... | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

### `assignees`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization... | No |  |
| `url` | string (uri) | No |  |

### `auto_merge`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `commit_message` | string | Yes | Commit message for the merge commit. |
| `commit_title` | string | Yes | Title for the merge commit message. |
| `enabled_by` | object | Yes |  |
| `merge_method` | enum: merge, squash, rebase | Yes | The merge method to use. |

#### `auto_merge.enabled_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

### `base`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | object | Yes | A git repository |
| `sha` | string | Yes |  |
| `user` | object | Yes |  |

#### `base.repo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_auto_merge` | boolean | No | Whether to allow auto-merge for pull requests. |
| `allow_forking` | boolean | No | Whether to allow private forks |
| `allow_merge_commit` | boolean | No | Whether to allow merge commits for pull requests. |
| `allow_rebase_merge` | boolean | No | Whether to allow rebase merges for pull requests. |
| `allow_squash_merge` | boolean | No | Whether to allow squash merges for pull requests. |
| `allow_update_branch` | boolean | No |  |
| `archive_url` | string (uri-template) | Yes |  |
| `archived` | boolean | Yes | Whether the repository is archived. |
| `assignees_url` | string (uri-template) | Yes |  |
| `blobs_url` | string (uri-template) | Yes |  |
| `branches_url` | string (uri-template) | Yes |  |
| `clone_url` | string (uri) | Yes |  |
| `collaborators_url` | string (uri-template) | Yes |  |
| `comments_url` | string (uri-template) | Yes |  |
| `commits_url` | string (uri-template) | Yes |  |
| `compare_url` | string (uri-template) | Yes |  |
| `contents_url` | string (uri-template) | Yes |  |
| `contributors_url` | string (uri) | Yes |  |
| `created_at` | any | Yes |  |
| `default_branch` | string | Yes | The default branch of the repository. |
| `delete_branch_on_merge` | boolean | No | Whether to delete head branches when pull requests are merged |
| `deployments_url` | string (uri) | Yes |  |
| `description` | string | Yes |  |
| `disabled` | boolean | No | Returns whether or not this repository is disabled. |
| `downloads_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `fork` | boolean | Yes |  |
| `forks` | integer | Yes |  |
| `forks_count` | integer | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `full_name` | string | Yes |  |
| `git_commits_url` | string (uri-template) | Yes |  |
| `git_refs_url` | string (uri-template) | Yes |  |
| `git_tags_url` | string (uri-template) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `has_downloads` | boolean | Yes | Whether downloads are enabled. |
| `has_issues` | boolean | Yes | Whether issues are enabled. |
| `has_pages` | boolean | Yes |  |
| `has_projects` | boolean | Yes | Whether projects are enabled. |
| `has_wiki` | boolean | Yes | Whether the wiki is enabled. |
| `has_discussions` | boolean | Yes | Whether discussions are enabled. |
| `homepage` | string | Yes |  |
| `hooks_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes | Unique identifier of the repository |
| `is_template` | boolean | No |  |
| `issue_comment_url` | string (uri-template) | Yes |  |
| `issue_events_url` | string (uri-template) | Yes |  |
| `issues_url` | string (uri-template) | Yes |  |
| `keys_url` | string (uri-template) | Yes |  |
| `labels_url` | string (uri-template) | Yes |  |
| `language` | string | Yes |  |
| `languages_url` | string (uri) | Yes |  |
| `license` | object | Yes |  |
| `master_branch` | string | No |  |
| `merge_commit_message` | enum: PR_BODY, PR_TITLE, BLANK | No | The default value for a merge commit message.

- `PR_TITLE` - default to the pull request's title.
- `PR_BODY` - default to the pull request's body.
- `BLANK` - default to a blank commit message. |
| `merge_commit_title` | enum: PR_TITLE, MERGE_MESSAGE | No | The default value for a merge commit title.

- `PR_TITLE` - default to the pull request's title.
- `MERGE_MESSAGE` - default to the classic title for a merge message (e.g., Merge pull request #123 from branch-name). |
| `merges_url` | string (uri) | Yes |  |
| `milestones_url` | string (uri-template) | Yes |  |
| `mirror_url` | string (uri) | Yes |  |
| `name` | string | Yes | The name of the repository. |
| `node_id` | string | Yes |  |
| `notifications_url` | string (uri-template) | Yes |  |
| `open_issues` | integer | Yes |  |
| `open_issues_count` | integer | Yes |  |
| `organization` | string | No |  |
| `owner` | object | Yes |  |
| `permissions` | object | No |  |
| `private` | boolean | Yes | Whether the repository is private or public. |
| `public` | boolean | No |  |
| `pulls_url` | string (uri-template) | Yes |  |
| `pushed_at` | any | Yes |  |
| `releases_url` | string (uri-template) | Yes |  |
| `role_name` | string | No |  |
| `size` | integer | Yes |  |
| `squash_merge_commit_message` | enum: PR_BODY, COMMIT_MESSAGES, BLANK | No | The default value for a squash merge commit message:

- `PR_BODY` - default to the pull request's body.
- `COMMIT_MESSAGES` - default to the branch's commit messages.
- `BLANK` - default to a blank commit message. |
| `squash_merge_commit_title` | enum: PR_TITLE, COMMIT_OR_PR_TITLE | No | The default value for a squash merge commit title:

- `PR_TITLE` - default to the pull request's title.
- `COMMIT_OR_PR_TITLE` - default to the commit's title (if only one commit) or the pull request's title (when more than one commit). |
| `ssh_url` | string | Yes |  |
| `stargazers` | integer | No |  |
| `stargazers_count` | integer | Yes |  |
| `stargazers_url` | string (uri) | Yes |  |
| `statuses_url` | string (uri-template) | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `svn_url` | string (uri) | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `topics` | string[] | Yes |  |
| `trees_url` | string (uri-template) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |
| `use_squash_pr_title_as_default` | boolean | No | Whether a squash merge commit can use the pull request title as default. |
| `visibility` | enum: public, private, internal | Yes |  |
| `watchers` | integer | Yes |  |
| `watchers_count` | integer | Yes |  |
| `web_commit_signoff_required` | boolean | No | Whether to require contributors to sign off on web-based commits |

#### `base.user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer (int64) | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

### `head`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | object | Yes | A git repository |
| `sha` | string | Yes |  |
| `user` | object | Yes |  |

#### `head.repo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_auto_merge` | boolean | No | Whether to allow auto-merge for pull requests. |
| `allow_forking` | boolean | No | Whether to allow private forks |
| `allow_merge_commit` | boolean | No | Whether to allow merge commits for pull requests. |
| `allow_rebase_merge` | boolean | No | Whether to allow rebase merges for pull requests. |
| `allow_squash_merge` | boolean | No | Whether to allow squash merges for pull requests. |
| `allow_update_branch` | boolean | No |  |
| `archive_url` | string (uri-template) | Yes |  |
| `archived` | boolean | Yes | Whether the repository is archived. |
| `assignees_url` | string (uri-template) | Yes |  |
| `blobs_url` | string (uri-template) | Yes |  |
| `branches_url` | string (uri-template) | Yes |  |
| `clone_url` | string (uri) | Yes |  |
| `collaborators_url` | string (uri-template) | Yes |  |
| `comments_url` | string (uri-template) | Yes |  |
| `commits_url` | string (uri-template) | Yes |  |
| `compare_url` | string (uri-template) | Yes |  |
| `contents_url` | string (uri-template) | Yes |  |
| `contributors_url` | string (uri) | Yes |  |
| `created_at` | any | Yes |  |
| `default_branch` | string | Yes | The default branch of the repository. |
| `delete_branch_on_merge` | boolean | No | Whether to delete head branches when pull requests are merged |
| `deployments_url` | string (uri) | Yes |  |
| `description` | string | Yes |  |
| `disabled` | boolean | No | Returns whether or not this repository is disabled. |
| `downloads_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `fork` | boolean | Yes |  |
| `forks` | integer | Yes |  |
| `forks_count` | integer | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `full_name` | string | Yes |  |
| `git_commits_url` | string (uri-template) | Yes |  |
| `git_refs_url` | string (uri-template) | Yes |  |
| `git_tags_url` | string (uri-template) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `has_downloads` | boolean | Yes | Whether downloads are enabled. |
| `has_issues` | boolean | Yes | Whether issues are enabled. |
| `has_pages` | boolean | Yes |  |
| `has_projects` | boolean | Yes | Whether projects are enabled. |
| `has_wiki` | boolean | Yes | Whether the wiki is enabled. |
| `has_discussions` | boolean | Yes | Whether discussions are enabled. |
| `homepage` | string | Yes |  |
| `hooks_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes | Unique identifier of the repository |
| `is_template` | boolean | No |  |
| `issue_comment_url` | string (uri-template) | Yes |  |
| `issue_events_url` | string (uri-template) | Yes |  |
| `issues_url` | string (uri-template) | Yes |  |
| `keys_url` | string (uri-template) | Yes |  |
| `labels_url` | string (uri-template) | Yes |  |
| `language` | string | Yes |  |
| `languages_url` | string (uri) | Yes |  |
| `license` | object | Yes |  |
| `master_branch` | string | No |  |
| `merge_commit_message` | enum: PR_BODY, PR_TITLE, BLANK | No | The default value for a merge commit message.

- `PR_TITLE` - default to the pull request's title.
- `PR_BODY` - default to the pull request's body.
- `BLANK` - default to a blank commit message. |
| `merge_commit_title` | enum: PR_TITLE, MERGE_MESSAGE | No | The default value for a merge commit title.

- `PR_TITLE` - default to the pull request's title.
- `MERGE_MESSAGE` - default to the classic title for a merge message (e.g., Merge pull request #123 from branch-name). |
| `merges_url` | string (uri) | Yes |  |
| `milestones_url` | string (uri-template) | Yes |  |
| `mirror_url` | string (uri) | Yes |  |
| `name` | string | Yes | The name of the repository. |
| `node_id` | string | Yes |  |
| `notifications_url` | string (uri-template) | Yes |  |
| `open_issues` | integer | Yes |  |
| `open_issues_count` | integer | Yes |  |
| `organization` | string | No |  |
| `owner` | object | Yes |  |
| `permissions` | object | No |  |
| `private` | boolean | Yes | Whether the repository is private or public. |
| `public` | boolean | No |  |
| `pulls_url` | string (uri-template) | Yes |  |
| `pushed_at` | any | Yes |  |
| `releases_url` | string (uri-template) | Yes |  |
| `role_name` | string | No |  |
| `size` | integer | Yes |  |
| `squash_merge_commit_message` | enum: PR_BODY, COMMIT_MESSAGES, BLANK | No | The default value for a squash merge commit message:

- `PR_BODY` - default to the pull request's body.
- `COMMIT_MESSAGES` - default to the branch's commit messages.
- `BLANK` - default to a blank commit message. |
| `squash_merge_commit_title` | enum: PR_TITLE, COMMIT_OR_PR_TITLE | No | The default value for a squash merge commit title:

- `PR_TITLE` - default to the pull request's title.
- `COMMIT_OR_PR_TITLE` - default to the commit's title (if only one commit) or the pull request's title (when more than one commit). |
| `ssh_url` | string | Yes |  |
| `stargazers` | integer | No |  |
| `stargazers_count` | integer | Yes |  |
| `stargazers_url` | string (uri) | Yes |  |
| `statuses_url` | string (uri-template) | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `svn_url` | string (uri) | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `topics` | string[] | Yes |  |
| `trees_url` | string (uri-template) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |
| `use_squash_pr_title_as_default` | boolean | No | Whether a squash merge commit can use the pull request title as default. |
| `visibility` | enum: public, private, internal | Yes |  |
| `watchers` | integer | Yes |  |
| `watchers_count` | integer | Yes |  |
| `web_commit_signoff_required` | boolean | No | Whether to require contributors to sign off on web-based commits |

#### `head.user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer (int64) | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

### `labels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | string | Yes | 6-character hex code, without the leading #, identifying the color |
| `default` | boolean | Yes |  |
| `description` | string | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes | The name of the label. |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the label |

### `merged_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization... | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

### `milestone`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `closed_at` | string (date-time) | Yes |  |
| `closed_issues` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `creator` | object | Yes |  |
| `description` | string | Yes |  |
| `due_on` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `labels_url` | string (uri) | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes | The number of the milestone. |
| `open_issues` | integer | Yes |  |
| `state` | enum: open, closed | Yes | The state of the milestone. |
| `title` | string | Yes | The title of the milestone. |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |

#### `milestone.creator`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization... | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

### `requested_teams`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deleted` | boolean | No |  |
| `description` | string | No | Description of the team |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes | Unique identifier of the team |
| `members_url` | string (uri-template) | No |  |
| `name` | string | Yes | Name of the team |
| `node_id` | string | No |  |
| `parent` | object | No |  |
| `permission` | string | No | Permission that the team will have for its repositories |
| `privacy` | enum: open, closed, secret | No |  |
| `repositories_url` | string (uri) | No |  |
| `slug` | string | No |  |
| `url` | string (uri) | No | URL for the team |

#### `requested_teams.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | Description of the team |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the team |
| `members_url` | string (uri-template) | Yes |  |
| `name` | string | Yes | Name of the team |
| `node_id` | string | Yes |  |
| `permission` | string | Yes | Permission that the team will have for its repositories |
| `privacy` | enum: open, closed, secret | Yes |  |
| `repositories_url` | string (uri) | Yes |  |
| `slug` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the team |

### `user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer (int64) | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization... | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

