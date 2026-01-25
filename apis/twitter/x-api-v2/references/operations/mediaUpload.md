# POST /2/media/upload

**Resource:** [Media](../resources/Media.md)
**Upload media**
**Operation ID:** `mediaUpload`

Uploads a media file for use in posts or other content.

## Request Body

**Content Types:** `application/json`, `multipart/form-data`

**Schema:** [MediaUploadRequestOneShot](../schemas/Media/MediaUploadRequestOneShot.md)

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
