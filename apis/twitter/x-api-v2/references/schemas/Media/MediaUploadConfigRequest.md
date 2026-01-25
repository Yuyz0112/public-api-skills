# MediaUploadConfigRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_owners` | UserId[] | No |  |
| `media_category` | [MediaCategory](MediaCategory.md) | No |  |
| `media_type` | enum: video/mp4, video/webm, video/mp2t... | No | The type of media. |
| `shared` | boolean | No | Whether this media is shared or not. |
| `total_bytes` | integer | No | The total size of the media upload in bytes. |

