# MediaUploadRequestOneShot

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_owners` | UserId[] | No |  |
| `media` | any | Yes |  |
| `media_category` | [MediaCategoryOneShot](MediaCategoryOneShot.md) | Yes |  |
| `media_type` | enum: text/srt, text/vtt, image/jpeg... | No | The type of image or subtitle. |
| `shared` | boolean | No | Whether this media is shared or not. |

