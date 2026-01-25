# POST /accounts/{account_id}/realtime/kit/{app_id}/recordings/track

**Resource:** [Recordings](../resources/Recordings.md)
**Start recording audio and video tracks**
**Operation ID:** `startTrackRecordingForAMeeting`

Starts a track recording in a meeting. Track recordings consist of "layers". Layers are used to map audio/video tracks in a meeting to output destinations. More information about track recordings is available in the [Track Recordings Guide Page](https://docs.realtime.cloudflare.com/guides/capabilities/recording/recording-overview).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
