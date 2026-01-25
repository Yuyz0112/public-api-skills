# release

A release.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `assets_url` | string (uri) | Yes |  |
| `upload_url` | string | Yes |  |
| `tarball_url` | string (uri) | Yes |  |
| `zipball_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `tag_name` | string | Yes | The name of the tag. |
| `target_commitish` | string | Yes | Specifies the commitish value that determines where the Git tag is created from. |
| `name` | string | Yes |  |
| `body` | string | No |  |
| `draft` | boolean | Yes | true to create a draft (unpublished) release, false to create a published one. |
| `prerelease` | boolean | Yes | Whether to identify the release as a prerelease or a full release. |
| `immutable` | boolean | No | Whether or not the release is immutable. |
| `created_at` | string (date-time) | Yes |  |
| `published_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | No |  |
| `author` | [simple-user](simple-user.md) | Yes |  |
| `assets` | release-asset[] | Yes |  |
| `body_html` | string | No |  |
| `body_text` | string | No |  |
| `mentions_count` | integer | No |  |
| `discussion_url` | string (uri) | No | The URL of the release discussion. |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |

