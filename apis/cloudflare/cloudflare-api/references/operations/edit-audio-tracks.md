# PATCH /accounts/{account_id}/stream/{identifier}/audio/{audio_identifier}

**Resource:** [Stream Audio Tracks](../resources/Stream-Audio-Tracks.md)
**Edit additional audio tracks on a video**
**Operation ID:** `edit-audio-tracks`

Edits additional audio tracks on a video. Editing the default status of an audio track to `true` will mark all other audio tracks on the video default status to `false`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |
| `audio_identifier` | path | stream_audio_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_editAudioTrack](../schemas/stream/stream-editAudioTrack.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edits additional audio tracks on a video. |
| 4XX | Edits additional audio tracks on a video response failure. |

**Success Response Schema:**

[stream_addAudioTrackResponse](../schemas/stream/stream-addAudioTrackResponse.md)

## Security

- **api_email**
- **api_key**
- **api_token**
