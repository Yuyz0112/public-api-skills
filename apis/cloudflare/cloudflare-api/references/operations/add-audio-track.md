# POST /accounts/{account_id}/stream/{identifier}/audio/copy

**Resource:** [Stream Audio Tracks](../resources/Stream-Audio-Tracks.md)
**Add audio tracks to a video**
**Operation ID:** `add-audio-track`

Adds an additional audio track to a video using the provided audio track URL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_copyAudioTrack](../schemas/stream/stream-copyAudioTrack.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add audio tracks to a video. |
| 4XX | Add audio tracks to a video response failure. |

**Success Response Schema:**

[stream_addAudioTrackResponse](../schemas/stream/stream-addAudioTrackResponse.md)

## Security

- **api_email**
- **api_key**
- **api_token**
