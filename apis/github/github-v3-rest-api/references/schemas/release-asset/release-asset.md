# release-asset

Data related to a release.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `browser_download_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `name` | string | Yes | The file name of the asset. |
| `label` | string | Yes |  |
| `state` | enum: uploaded, open | Yes | State of the release asset. |
| `content_type` | string | Yes |  |
| `size` | integer | Yes |  |
| `digest` | string | Yes |  |
| `download_count` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `uploader` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |

