# webhook-issue-comment-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | Yes |  |
| `comment` | object | Yes | The [comment](https://docs.github.com/rest/issues/comments#get-an-issue-comment) itself. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `issue` | any | Yes | The [issue](https://docs.github.com/rest/issues/issues#get-an-issue) the comment belongs to. |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `comment`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `body` | string | Yes | Contents of the issue comment |
| `created_at` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes | Unique identifier of the issue comment |
| `issue_url` | string (uri) | Yes |  |
| `node_id` | string | Yes |  |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | Yes |  |
| `reactions` | object | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes | URL for the issue comment |
| `user` | object | Yes |  |

#### `comment.reactions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `+1` | integer | Yes |  |
| `-1` | integer | Yes |  |
| `confused` | integer | Yes |  |
| `eyes` | integer | Yes |  |
| `heart` | integer | Yes |  |
| `hooray` | integer | Yes |  |
| `laugh` | integer | Yes |  |
| `rocket` | integer | Yes |  |
| `total_count` | integer | Yes |  |
| `url` | string (uri) | Yes |  |

#### `comment.user`

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

