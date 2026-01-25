# GET /accounts/{account_id}/stream/{identifier}/audio

**Resource:** [Stream Audio Tracks](../resources/Stream-Audio-Tracks.md)
**List additional audio tracks on a video**
**Operation ID:** `list-audio-tracks`

Lists additional audio tracks on a video. Note this API will not return information for audio attached to the video upload.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Lists additional audio tracks on a video. |
| 4XX | Lists additional audio tracks on a video response failure. |

**Success Response Schema:**

[stream_listAudioTrackResponse](../schemas/stream/stream-listAudioTrackResponse.md)

## Security

- **api_email**
- **api_key**
- **api_token**
