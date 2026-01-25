# MediaUploadAppendResponse

A response from getting a media upload request status.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expires_at` | integer (int64) | No | Unix epoch time in seconds after when the upload session expires. |

