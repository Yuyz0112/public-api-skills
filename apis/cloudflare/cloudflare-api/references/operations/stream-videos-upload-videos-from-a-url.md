# POST /accounts/{account_id}/stream/copy

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Upload videos from a URL**
**Operation ID:** `stream-videos-upload-videos-from-a-url`

Uploads a video to Stream from a provided URL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `Upload-Creator` | header | stream_creator | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_video_copy_request](../schemas/stream/stream-video-copy-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload videos from a URL response. |
| 4XX | Upload videos from a URL response failure. |

**Success Response Schema:**

[stream_video_response_single](../schemas/stream/stream-video-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
