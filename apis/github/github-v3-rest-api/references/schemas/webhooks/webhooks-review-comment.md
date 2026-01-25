# webhooks_review_comment

The [comment](https://docs.github.com/rest/pulls/comments#get-a-review-comment-for-a-pull-request) itself.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `_links` | object | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `body` | string | Yes | The text of the comment. |
| `commit_id` | string | Yes | The SHA of the commit to which the comment applies. |
| `created_at` | string (date-time) | Yes |  |
| `diff_hunk` | string | Yes | The diff of the line that the comment refers to. |
| `html_url` | string (uri) | Yes | HTML URL for the pull request review comment. |
| `id` | integer | Yes | The ID of the pull request review comment. |
| `in_reply_to_id` | integer | No | The comment ID to reply to. |
| `line` | integer | Yes | The line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `node_id` | string | Yes | The node ID of the pull request review comment. |
| `original_commit_id` | string | Yes | The SHA of the original commit to which the comment applies. |
| `original_line` | integer | Yes | The line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `original_position` | integer | Yes | The index of the original line in the diff to which the comment applies. |
| `original_start_line` | integer | Yes | The first line of the range for a multi-line comment. |
| `path` | string | Yes | The relative path of the file to which the comment applies. |
| `position` | integer | Yes | The line index in the diff to which the comment applies. |
| `pull_request_review_id` | integer | Yes | The ID of the pull request review to which the comment belongs. |
| `pull_request_url` | string (uri) | Yes | URL for the pull request that the review comment belongs to. |
| `reactions` | object | Yes |  |
| `side` | enum: LEFT, RIGHT | Yes | The side of the first line of the range for a multi-line comment. |
| `start_line` | integer | Yes | The first line of the range for a multi-line comment. |
| `start_side` | enum: LEFT, RIGHT,  | Yes | The side of the first line of the range for a multi-line comment. |
| `subject_type` | enum: line, file | No | The level at which the comment is targeted, can be a diff line or a file. |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes | URL for the pull request review comment |
| `user` | object | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html` | object | Yes |  |
| `pull_request` | object | Yes |  |
| `self` | object | Yes |  |

#### `_links.html`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.self`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

### `reactions`

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
| `type` | enum: Bot, User, Organization | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

