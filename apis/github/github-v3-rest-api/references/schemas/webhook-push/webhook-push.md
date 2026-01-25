# webhook-push

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string | Yes | The SHA of the most recent commit on `ref` after the push. |
| `base_ref` | [webhooks_nullable_string](webhooks-nullable-string.md) | Yes |  |
| `before` | string | Yes | The SHA of the most recent commit on `ref` before the push. |
| `commits` | object[] | Yes | An array of commit objects describing the pushed commits. (Pushed commits are all commits that are included in the `compare` between the `before` commit and the `after` commit.) The array includes a maximum of 2048 commits. If necessary, you can use the [Commits API](https://docs.github.com/rest/commits) to fetch additional commits. |
| `compare` | string | Yes | URL that shows the changes in this `ref` update, from the `before` commit to the `after` commit. For a newly created `ref` that is directly based on the default branch, this is the comparison between the head of the default branch and the `after` commit. Otherwise, this shows all commits until the `after` commit. |
| `created` | boolean | Yes | Whether this push created the `ref`. |
| `deleted` | boolean | Yes | Whether this push deleted the `ref`. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `forced` | boolean | Yes | Whether this push was a force push of the `ref`. |
| `head_commit` | object | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pusher` | object | Yes | Metaproperties for Git author/committer information. |
| `ref` | string | Yes | The full git ref that was pushed. Example: `refs/heads/main` or `refs/tags/v3.14.1`. |
| `repository` | object | Yes | A git repository |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `commits`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `added` | string[] | No | An array of files added in the commit. A maximum of 3000 changed files will be reported per commit. |
| `author` | object | Yes | Metaproperties for Git author/committer information. |
| `committer` | object | Yes | Metaproperties for Git author/committer information. |
| `distinct` | boolean | Yes | Whether this commit is distinct from any that have been pushed before. |
| `id` | string | Yes |  |
| `message` | string | Yes | The commit message. |
| `modified` | string[] | No | An array of files modified by the commit. A maximum of 3000 changed files will be reported per commit. |
| `removed` | string[] | No | An array of files removed in the commit. A maximum of 3000 changed files will be reported per commit. |
| `timestamp` | string (date-time) | Yes | The ISO 8601 timestamp of the commit. |
| `tree_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL that points to the commit API resource. |

#### `commits.author`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | No |  |
| `email` | string (email) | Yes |  |
| `name` | string | Yes | The git author's name. |
| `username` | string | No |  |

#### `commits.committer`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | No |  |
| `email` | string (email) | Yes |  |
| `name` | string | Yes | The git author's name. |
| `username` | string | No |  |

### `head_commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `added` | string[] | No | An array of files added in the commit. |
| `author` | object | Yes | Metaproperties for Git author/committer information. |
| `committer` | object | Yes | Metaproperties for Git author/committer information. |
| `distinct` | boolean | Yes | Whether this commit is distinct from any that have been pushed before. |
| `id` | string | Yes |  |
| `message` | string | Yes | The commit message. |
| `modified` | string[] | No | An array of files modified by the commit. |
| `removed` | string[] | No | An array of files removed in the commit. |
| `timestamp` | string (date-time) | Yes | The ISO 8601 timestamp of the commit. |
| `tree_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL that points to the commit API resource. |

#### `head_commit.author`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | No |  |
| `email` | string (email) | Yes |  |
| `name` | string | Yes | The git author's name. |
| `username` | string | No |  |

#### `head_commit.committer`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | No |  |
| `email` | string (email) | Yes |  |
| `name` | string | Yes | The git author's name. |
| `username` | string | No |  |

### `pusher`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string (date-time) | No |  |
| `email` | string (email) | No |  |
| `name` | string | Yes | The git author's name. |
| `username` | string | No |  |

### `repository`

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
| `custom_properties` | object | No | The custom properties that were defined for the repository. The keys are the custom property names, and the values are the corresponding custom property values. |
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
| `visibility` | enum: public, private, internal | Yes |  |
| `watchers` | integer | Yes |  |
| `watchers_count` | integer | Yes |  |
| `web_commit_signoff_required` | boolean | No | Whether to require contributors to sign off on web-based commits |

#### `repository.license`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes |  |
| `name` | string | Yes |  |
| `node_id` | string | Yes |  |
| `spdx_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |

#### `repository.owner`

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

#### `repository.permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | Yes |  |
| `maintain` | boolean | No |  |
| `pull` | boolean | Yes |  |
| `push` | boolean | Yes |  |
| `triage` | boolean | No |  |

