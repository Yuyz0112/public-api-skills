# GET /files.info

**Resource:** [files](../resources/files.md)
**Operation ID:** `files_info`

Gets information about a file.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `files:read` |
| `file` | query | string | No | Specify a file by providing its ID. |
| `count` | query | string | No |  |
| `page` | query | string | No |  |
| `limit` | query | integer | No | The maximum number of items to return. Fewer than the requested number of items may be returned, even if the end of the list hasn't been reached. |
| `cursor` | query | string | No | Parameter for pagination. File comments are paginated for a single file. Set `cursor` equal to the `next_cursor` attribute returned by the previous request's `response_metadata`. This parameter is optional, but pagination is mandatory: the default value simply fetches the first "page" of the collection of comments. See [pagination](/docs/pagination) for more details. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: files:read
