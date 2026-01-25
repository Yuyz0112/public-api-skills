# webhook-commit-comment-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | Yes | The action performed. Can be `created`. |
| `comment` | object | Yes | The [commit comment](${externalDocsUpapp/api/description/components/schemas/webhooks/issue-comment-created.yamlrl}/rest/commits/comments#get-a-commit-comment) resource. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `comment`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `body` | string | Yes | The text of the comment. |
| `commit_id` | string | Yes | The SHA of the commit to which the comment applies. |
| `created_at` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | The ID of the commit comment. |
| `line` | integer | Yes | The line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `node_id` | string | Yes | The node ID of the commit comment. |
| `path` | string | Yes | The relative path of the file to which the comment applies. |
| `position` | integer | Yes | The line index in the diff to which the comment applies. |
| `reactions` | object | No |  |
| `updated_at` | string | Yes |  |
| `url` | string (uri) | Yes |  |
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

