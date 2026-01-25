# webhooks_release

The [release](https://docs.github.com/rest/releases/releases/#get-a-release) object.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assets` | object[] | Yes |  |
| `assets_url` | string (uri) | Yes |  |
| `author` | object | Yes |  |
| `body` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `discussion_url` | string (uri) | No |  |
| `draft` | boolean | Yes | Whether the release is a draft or published |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `immutable` | boolean | Yes | Whether or not the release is immutable. |
| `name` | string | Yes |  |
| `node_id` | string | Yes |  |
| `prerelease` | boolean | Yes | Whether the release is identified as a prerelease or a full release. |
| `published_at` | string (date-time) | Yes |  |
| `reactions` | object | No |  |
| `tag_name` | string | Yes | The name of the tag. |
| `tarball_url` | string (uri) | Yes |  |
| `target_commitish` | string | Yes | Specifies the commitish value that determines where the Git tag is created from. |
| `upload_url` | string (uri-template) | Yes |  |
| `url` | string (uri) | Yes |  |
| `zipball_url` | string (uri) | Yes |  |

## Nested Fields

### `assets`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `browser_download_url` | string (uri) | Yes |  |
| `content_type` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `download_count` | integer | Yes |  |
| `id` | integer | Yes |  |
| `label` | string | Yes |  |
| `name` | string | Yes | The file name of the asset. |
| `node_id` | string | Yes |  |
| `size` | integer | Yes |  |
| `digest` | string | Yes |  |
| `state` | enum: uploaded | Yes | State of the release asset. |
| `updated_at` | string (date-time) | Yes |  |
| `uploader` | object | No |  |
| `url` | string (uri) | Yes |  |

#### `assets.uploader`

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

### `author`

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

