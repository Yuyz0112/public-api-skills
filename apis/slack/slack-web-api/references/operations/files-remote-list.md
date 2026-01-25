# GET /files.remote.list

**Resource:** [files.remote](../resources/files-remote.md)
**Operation ID:** `files_remote_list`

Retrieve information about a remote file added to Slack

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `remote_files:read` |
| `channel` | query | string | No | Filter files appearing in a specific channel, indicated by its ID. |
| `ts_from` | query | number | No | Filter files created after this timestamp (inclusive). |
| `ts_to` | query | number | No | Filter files created before this timestamp (inclusive). |
| `limit` | query | integer | No | The maximum number of items to return. |
| `cursor` | query | string | No | Paginate through collections of data by setting the `cursor` parameter to a `next_cursor` attribute returned by a previous request's `response_metadata`. Default value fetches the first "page" of the collection. See [pagination](/docs/pagination) for more detail. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: remote_files:read
