# stream_direct_upload_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowedOrigins` | [stream_allowedOrigins](stream-allowedOrigins.md) | No |  |
| `creator` | [stream_creator](stream-creator.md) | No |  |
| `expiry` | string (date-time) | No | The date and time after upload when videos will not be accepted. |
| `maxDurationSeconds` | [stream_maxDurationSeconds](stream-maxDurationSeconds.md) | Yes |  |
| `meta` | [stream_media_metadata](stream-media-metadata.md) | No |  |
| `requireSignedURLs` | [stream_requireSignedURLs](stream-requireSignedURLs.md) | No |  |
| `scheduledDeletion` | [stream_scheduledDeletion](stream-scheduledDeletion.md) | No |  |
| `thumbnailTimestampPct` | [stream_thumbnailTimestampPct](stream-thumbnailTimestampPct.md) | No |  |
| `watermark` | [stream_watermark_at_upload](stream-watermark-at-upload.md) | No |  |

