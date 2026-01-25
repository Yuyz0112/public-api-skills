# review-comment

Legacy Review Comment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `pull_request_review_id` | integer (int64) | Yes |  |
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `diff_hunk` | string | Yes |  |
| `path` | string | Yes |  |
| `position` | integer | Yes |  |
| `original_position` | integer | Yes |  |
| `commit_id` | string | Yes |  |
| `original_commit_id` | string | Yes |  |
| `in_reply_to_id` | integer | No |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `body` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `pull_request_url` | string (uri) | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `_links` | object | Yes |  |
| `body_text` | string | No |  |
| `body_html` | string | No |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |
| `side` | enum: LEFT, RIGHT | No | The side of the first line of the range for a multi-line comment. |
| `start_side` | enum: LEFT, RIGHT | No | The side of the first line of the range for a multi-line comment. |
| `line` | integer | No | The line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `original_line` | integer | No | The original line of the blob to which the comment applies. The last line of the range for a multi-line comment |
| `start_line` | integer | No | The first line of the range for a multi-line comment. |
| `original_start_line` | integer | No | The original first line of the range for a multi-line comment. |
| `subject_type` | enum: line, file | No | The level at which the comment is targeted, can be a diff line or a file. |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | [link](link.md) | Yes |  |
| `html` | [link](link.md) | Yes |  |
| `pull_request` | [link](link.md) | Yes |  |

