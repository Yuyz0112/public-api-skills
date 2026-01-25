# stream_video_copy_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowedOrigins` | [stream_allowedOrigins](stream-allowedOrigins.md) | No |  |
| `creator` | [stream_creator](stream-creator.md) | No |  |
| `meta` | [stream_media_metadata](stream-media-metadata.md) | No |  |
| `requireSignedURLs` | [stream_requireSignedURLs](stream-requireSignedURLs.md) | No |  |
| `scheduledDeletion` | [stream_scheduledDeletion](stream-scheduledDeletion.md) | No |  |
| `thumbnailTimestampPct` | [stream_thumbnailTimestampPct](stream-thumbnailTimestampPct.md) | No |  |
| `url` | string (uri) | Yes | A video's URL. The server must be publicly routable and support `HTTP HEAD` requests and `HTTP GET` range requests. The server should respond to `HTTP HEAD` requests with a `content-range` header that includes the size of the file. |
| `watermark` | [stream_watermark_at_upload](stream-watermark-at-upload.md) | No |  |

