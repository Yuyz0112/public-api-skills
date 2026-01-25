# MessageAttachmentResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `filename` | string | Yes |  |
| `size` | integer (int32) | Yes |  |
| `url` | string (uri) | Yes |  |
| `proxy_url` | string (uri) | Yes |  |
| `width` | integer (int32) | No |  |
| `height` | integer (int32) | No |  |
| `duration_secs` | number (double) | No |  |
| `waveform` | string | No |  |
| `description` | string | No |  |
| `content_type` | string | No |  |
| `ephemeral` | boolean | No |  |
| `title` | string,null | No |  |
| `application` | [ApplicationResponse](ApplicationResponse.md) | No |  |
| `clip_created_at` | string (date-time) | No |  |
| `clip_participants` | UserResponse[] | No |  |

