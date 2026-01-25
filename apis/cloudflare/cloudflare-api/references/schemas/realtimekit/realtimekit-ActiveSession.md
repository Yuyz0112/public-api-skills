# realtimekit_ActiveSession

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `associated_id` | string | Yes | ID of the meeting this session is associated with. In the case of V2 meetings, it is always a UUID. In V1 meetings, it is a room name of the form `abcdef-ghijkl` |
| `breakout_rooms` | realtimekit_ActiveSession[] | No |  |
| `created_at` | string | Yes | timestamp when session created |
| `ended_at` | string | No | timestamp when session ended |
| `id` | string | Yes | ID of the session |
| `live_participants` | number | Yes | number of participants currently in the session |
| `max_concurrent_participants` | number | Yes | number of maximum participants that were in the session |
| `meeting_display_name` | string | Yes | Title of the meeting this session belongs to |
| `meta` | object | No | Any meta data about session. |
| `minutes_consumed` | number | Yes | number of minutes consumed since the session started |
| `organization_id` | string | Yes | App id that hosted this session |
| `started_at` | string | Yes | timestamp when session started |
| `status` | enum: LIVE, ENDED | Yes | current status of session |
| `type` | enum: meeting, livestream, participant | Yes | type of session |
| `updated_at` | string | Yes | timestamp when session was last updated |

