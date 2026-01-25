# artifact

An artifact

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `name` | string | Yes | The name of the artifact. |
| `size_in_bytes` | integer | Yes | The size in bytes of the artifact. |
| `url` | string | Yes |  |
| `archive_download_url` | string | Yes |  |
| `expired` | boolean | Yes | Whether or not the artifact has expired. |
| `created_at` | string (date-time) | Yes |  |
| `expires_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `digest` | string | No | The SHA256 digest of the artifact. This field will only be populated on artifacts uploaded with upload-artifact v4 or newer. For older versions, this field will be null. |
| `workflow_run` | object | No |  |

## Nested Fields

### `workflow_run`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `repository_id` | integer | No |  |
| `head_repository_id` | integer | No |  |
| `head_branch` | string | No |  |
| `head_sha` | string | No |  |

