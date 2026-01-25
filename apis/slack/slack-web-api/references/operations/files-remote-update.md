# POST /files.remote.update

**Resource:** [files.remote](../resources/files-remote.md)
**Operation ID:** `files_remote_update`

Updates an existing remote file.

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: remote_files:write
