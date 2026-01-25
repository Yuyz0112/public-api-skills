# POST /files.upload

**Resource:** [files](../resources/files.md)
**Operation ID:** `files_upload`

Uploads or creates a file.

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success response after uploading a file to a channel with an initial message |
| default | Typical error response |

## Security

- **slackAuth**: files:write:user
