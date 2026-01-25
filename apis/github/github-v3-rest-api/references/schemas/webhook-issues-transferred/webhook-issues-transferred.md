# webhook-issues-transferred

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: transferred | Yes |  |
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `issue` | [webhooks_issue_2](webhooks-issue-2.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `new_issue` | object | Yes | The [issue](https://docs.github.com/rest/issues/issues#get-an-issue) itself. |
| `new_repository` | object | Yes | A git repository |

#### `changes.new_issue`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_lock_reason` | enum: resolved, off-topic, too heated... | Yes |  |
| `assignee` | object | No |  |
| `assignees` | object[] | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `body` | string | Yes | Contents of the issue |
| `closed_at` | string (date-time) | Yes |  |
| `comments` | integer | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `draft` | boolean | No |  |
| `events_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes |  |
| `labels` | object[] | No |  |
| `labels_url` | string (uri-template) | Yes |  |
| `locked` | boolean | No |  |
| `milestone` | object | Yes | A collection of related issues and pull requests. |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `performed_via_github_app` | object | No | GitHub apps are a new way to extend GitHub. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks. GitHub apps are first class actors within GitHub. |
| `pull_request` | object | No |  |
| `reactions` | object | Yes |  |
| `repository_url` | string (uri) | Yes |  |
| `sub_issues_summary` | [sub-issues-summary](sub-issues-summary.md) | No |  |
| `issue_dependencies_summary` | [issue-dependencies-summary](issue-dependencies-summary.md) | No |  |
| `issue_field_values` | issue-field-value[] | No |  |
| `state` | enum: open, closed | No | State of the issue; either 'open' or 'closed' |
| `state_reason` | string | No |  |
| `timeline_url` | string (uri) | No |  |
| `title` | string | Yes | Title of the issue |
| `type` | [issue-type](issue-type.md) | No |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes | URL for the issue |
| `user` | object | Yes |  |

#### `changes.new_repository`

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

