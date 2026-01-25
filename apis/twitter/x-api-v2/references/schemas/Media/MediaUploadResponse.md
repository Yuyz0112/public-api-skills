# MediaUploadResponse

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
| `expires_after_secs` | integer (int32) | No | Number of seconds after which upload session expires. |
| `id` | [MediaId](MediaId.md) | Yes |  |
| `media_key` | [MediaKey](MediaKey.md) | Yes |  |
| `processing_info` | [ProcessingInfo](ProcessingInfo.md) | No |  |
| `size` | integer (int32) | No | Size of the upload |

