# images_image_direct_upload_request_v2

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `creator` | string | No | Can set the creator field with an internal user ID. |
| `expiry` | string (date-time) | No | The date after which the upload will not be accepted. Minimum: Now + 2 minutes. Maximum: Now + 6 hours. |
| `id` | string | No | Optional Image Custom ID. Up to 1024 chars. Can include any number of subpaths, and utf8 characters. Cannot start nor end with a / (forward slash). Cannot be a UUID. |
| `metadata` | object | No | User modifiable key-value store. Can be used for keeping references to another system of record, for managing images. |
| `requireSignedURLs` | boolean | No | Indicates whether the image requires a signature token to be accessed. |

