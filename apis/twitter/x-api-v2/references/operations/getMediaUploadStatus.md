# GET /2/media/upload

**Resource:** [Media](../resources/Media.md)
**Get Media upload status**
**Operation ID:** `getMediaUploadStatus`

Retrieves the status of a Media upload by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `media_id` | query | MediaId | Yes | Media id for the requested media upload status. |
| `command` | query | enum: STATUS | No | The command for the media upload request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[MediaUploadResponse](../schemas/Media/MediaUploadResponse.md)

## Security

- **OAuth2UserToken**: media.write
- **UserToken**
