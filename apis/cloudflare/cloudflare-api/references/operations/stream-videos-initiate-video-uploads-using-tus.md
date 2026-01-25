# POST /accounts/{account_id}/stream

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Initiate video uploads using TUS**
**Operation ID:** `stream-videos-initiate-video-uploads-using-tus`

Initiates a video upload using the TUS protocol. On success, the server responds with a status code 201 (created) and includes a `location` header to indicate where the content should be uploaded. Refer to https://tus.io for protocol details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Tus-Resumable` | header | stream_tus_resumable | Yes |  |
| `Upload-Creator` | header | stream_creator | No |  |
| `Upload-Length` | header | stream_upload_length | Yes |  |
| `Upload-Metadata` | header | stream_upload_metadata | No |  |
| `account_id` | path | stream_account_identifier | Yes |  |
| `direct_user` | query | stream_direct_user | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Initiate video uploads using TUS response. |
| 4XX | Initiate video uploads using TUS response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
