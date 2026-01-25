# GET /files.remote.info

**Resource:** [files.remote](../resources/files-remote.md)
**Operation ID:** `files_remote_info`

Retrieve information about a remote file added to Slack

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `remote_files:read` |
| `file` | query | string | No | Specify a file by providing its ID. |
| `external_id` | query | string | No | Creator defined GUID for the file. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: remote_files:read
