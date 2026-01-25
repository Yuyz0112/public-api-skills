# pull-request-review-comment

Pull Request Review Comments are comments on a portion of the Pull Request's diff.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | Yes | URL for the pull request review comment |
| `pull_request_review_id` | integer (int64) | Yes | The ID of the pull request review to which the comment belongs. |
| `id` | integer (int64) | Yes | The ID of the pull request review comment. |
| `node_id` | string | Yes | The node ID of the pull request review comment. |
| `diff_hunk` | string | Yes | The diff of the line that the comment refers to. |
| `path` | string | Yes | The relative path of the file to which the comment applies. |
| `position` | integer | No | The line index in the diff to which the comment applies. This field is closing down; use `line` instead. |
| `original_position` | integer | No | The index of the original line in the diff to which the comment applies. This field is closing down; use `original_line` instead. |
| `commit_id` | string | Yes | The SHA of the commit to which the comment applies. |
| `original_commit_id` | string | Yes | The SHA of the original commit to which the comment applies. |
| `in_reply_to_id` | integer | No | The comment ID to reply to. |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `body` | string | Yes | The text of the comment. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes | HTML URL for the pull request review comment. |
| `pull_request_url` | string (uri) | Yes | URL for the pull request that the review comment belongs to. |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `_links` | object | Yes |  |
| `start_line` | integer | No | The first line of the range for a multi-line comment. |
| `original_start_line` | integer | No | The first line of the range for a multi-line comment. |
| `start_side` | enum: LEFT, RIGHT | No | The side of the first line of the range for a multi-line comment. |
| `line` | integer | No | The line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `original_line` | integer | No | The line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `side` | enum: LEFT, RIGHT | No | The side of the diff to which the comment applies. The side of the last line of the range for a multi-line comment |
| `subject_type` | enum: line, file | No | The level at which the comment is targeted, can be a diff line or a file. |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |
| `body_html` | string | No |  |
| `body_text` | string | No |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | object | Yes |  |
| `html` | object | Yes |  |
| `pull_request` | object | Yes |  |

#### `_links.self`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri) | Yes |  |

#### `_links.html`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri) | Yes |  |

#### `_links.pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri) | Yes |  |

