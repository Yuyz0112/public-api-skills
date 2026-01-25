# stream_copyAudioTrack

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | [stream_audio_label](stream-audio-label.md) | Yes |  |
| `url` | string (uri) | No | An audio track URL. The server must be publicly routable and support `HTTP HEAD` requests and `HTTP GET` range requests. The server should respond to `HTTP HEAD` requests with a `content-range` header that includes the size of the file. |

