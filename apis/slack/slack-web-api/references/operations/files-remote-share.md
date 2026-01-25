# GET /files.remote.share

**Resource:** [files.remote](../resources/files-remote.md)
**Operation ID:** `files_remote_share`

Share a remote file into a channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `remote_files:share` |
| `file` | query | string | No | Specify a file registered with Slack by providing its ID. Either this field or `external_id` or both are required. |
| `external_id` | query | string | No | The globally unique identifier (GUID) for the file, as set by the app registering the file with Slack.  Either this field or `file` or both are required. |
| `channels` | query | string | No | Comma-separated list of channel IDs where the file will be shared. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: remote_files:share
