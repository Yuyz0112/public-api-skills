# POST /2/media/upload/{id}/finalize

**Resource:** [Media](../resources/Media.md)
**Finalize Media upload**
**Operation ID:** `finalizeMediaUpload`

Finalizes a Media upload request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | MediaId | Yes | The media id of the targeted media to finalize. |

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
