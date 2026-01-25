# webhook-team-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `repository` | object | No | A git repository |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `team` | [webhooks_team_1](webhooks-team-1.md) | Yes |  |

## Nested Fields

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

