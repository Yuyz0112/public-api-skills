# stream_live_input_recording_settings

Records the input to a Cloudflare Stream video. Behavior depends on the mode. In most cases, the video will initially be viewable as a live video and transition to on-demand after a condition is satisfied.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowedOrigins` | [stream_live_input_recording_allowedOrigins](stream-live-input-recording-allowedOrigins.md) | No |  |
| `hideLiveViewerCount` | [stream_live_input_recording_hideLiveViewerCount](stream-live-input-recording-hideLiveViewerCount.md) | No |  |
| `mode` | [stream_live_input_recording_mode](stream-live-input-recording-mode.md) | No |  |
| `requireSignedURLs` | [stream_live_input_recording_requireSignedURLs](stream-live-input-recording-requireSignedURLs.md) | No |  |
| `timeoutSeconds` | [stream_live_input_recording_timeoutSeconds](stream-live-input-recording-timeoutSeconds.md) | No |  |

