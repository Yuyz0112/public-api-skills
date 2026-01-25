# realtimekit_LivestreamBase

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | The timestamp at which the livestream was created. The time is returned in ISO format. |
| `disabled` | boolean | No | Specifies if the livestream was disabled. |
| `id` | string | No | The livestream ID. |
| `ingest_server` | string | No | The server URL to which the RTMP encoder sends the video and audio data. |
| `meeting_id` | string | No | ID of the meeting. |
| `name` | string | No | Name of the livestream. |
| `org_id` | string | No |  |
| `playback_url` | string | No | The web address that viewers can use to watch the livestream. |
| `status` | enum: LIVE, IDLE, ERRORED... | No | The status of the livestream. |
| `stream_key` | string | No | Unique key for accessing each livestream. |
| `updated_at` | string (date-time) | No | The timestamp at which the livestream was updated. The time is returned in ISO format. |

