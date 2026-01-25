# realtimekit_Meeting

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | Yes | Timestamp the object was created at. The time is returned in ISO format. |
| `id` | string (uuid) | Yes | ID of the meeting. |
| `live_stream_on_start` | boolean | No | Specifies if the meeting should start getting livestreamed on start. |
| `persist_chat` | boolean | No | Specifies if Chat within a meeting should persist for a week. |
| `record_on_start` | boolean | No | Specifies if the meeting should start getting recorded as soon as someone joins the meeting. |
| `session_keep_alive_time_in_secs` | number | No | Time in seconds, for which a session remains active, after the last participant has left the meeting. |
| `status` | enum: ACTIVE, INACTIVE | No | Whether the meeting is `ACTIVE` or `INACTIVE`. Users will not be able to join an `INACTIVE` meeting. |
| `summarize_on_end` | boolean | No | Automatically generate summary of meetings using transcripts. Requires Transcriptions to be enabled, and can be retrieved via Webhooks or summary API. |
| `title` | string | No | Title of the meeting. |
| `updated_at` | string (date-time) | Yes | Timestamp the object was updated at. The time is returned in ISO format. |

