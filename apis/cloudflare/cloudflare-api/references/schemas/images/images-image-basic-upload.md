# images_image_basic_upload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `creator` | string | No | Can set the creator field with an internal user ID. |
| `file` | string (binary) | No | An image binary data. Only needed when type is uploading a file. |
| `id` | string | No | An optional custom unique identifier for your image. |
| `metadata` | object | No | User modifiable key-value store. Can use used for keeping references to another system of record for managing images. |
| `requireSignedURLs` | boolean | No | Indicates whether the image requires a signature token for the access. |
| `url` | string | No | A URL to fetch an image from origin. Only needed when type is uploading from a URL. |

