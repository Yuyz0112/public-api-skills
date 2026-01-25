# POST /2/media/upload/initialize

**Resource:** [Media](../resources/Media.md)
**Initialize media upload**
**Operation ID:** `initializeMediaUpload`

Initializes a media upload.

## Request Body

**Content Types:** `application/json`

**Schema:** [MediaUploadConfigRequest](../schemas/Media/MediaUploadConfigRequest.md)

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
