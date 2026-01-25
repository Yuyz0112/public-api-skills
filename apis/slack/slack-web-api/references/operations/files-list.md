# GET /files.list

**Resource:** [files](../resources/files.md)
**Operation ID:** `files_list`

List for a team, in a channel, or from a user with applied filters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `files:read` |
| `user` | query | string | No | Filter files created by a single user. |
| `channel` | query | string | No | Filter files appearing in a specific channel, indicated by its ID. |
| `ts_from` | query | number | No | Filter files created after this timestamp (inclusive). |
| `ts_to` | query | number | No | Filter files created before this timestamp (inclusive). |
| `types` | query | string | No | Filter files by type ([see below](#file_types)). You can pass multiple values in the types argument, like `types=spaces,snippets`.The default value is `all`, which does not filter the list. |
| `count` | query | string | No |  |
| `page` | query | string | No |  |
| `show_files_hidden_by_limit` | query | boolean | No | Show truncated file info for files hidden due to being too old, and the team who owns the file being over the file limit. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: files:read
