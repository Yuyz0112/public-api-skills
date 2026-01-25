# DELETE /accounts/{account_id}/stream/{identifier}/audio/{audio_identifier}

**Resource:** [Stream Audio Tracks](../resources/Stream-Audio-Tracks.md)
**Delete additional audio tracks on a video**
**Operation ID:** `delete-audio-tracks`

Deletes additional audio tracks on a video. Deleting a default audio track is not allowed. You must assign another audio track as default prior to deletion.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |
| `audio_identifier` | path | stream_audio_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deletes additional audio tracks on a video. |
| 4XX | Deletes additional audio tracks on a video response failure. |

**Success Response Schema:**

[stream_deleted_response](../schemas/stream/stream-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
