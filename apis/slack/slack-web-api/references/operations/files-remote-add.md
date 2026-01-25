# POST /files.remote.add

**Resource:** [files.remote](../resources/files-remote.md)
**Operation ID:** `files_remote_add`

Adds a file from a remote service

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: remote_files:write
