# GET /v1/files/{file_key}/versions

**Resource:** [Files](../resources/Files.md)
**Get versions of a file**
**Operation ID:** `getFileVersions`

This endpoint fetches the version history of a file, allowing you to see the progression of a file over time. You can then use this information to render a specific version of the file, via another endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to get version history from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `page_size` | query | number | No | The number of items returned in a page of the response. If not included, `page_size` is `30`. |
| `before` | query | number | No | A version ID for one of the versions in the history. Gets versions before this ID. Used for paginating. If the response is not paginated, this link returns the same data in the current response. |
| `after` | query | number | No | A version ID for one of the versions in the history. Gets versions after this ID. Used for paginating. If the response is not paginated, this property is not included. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_versions:read, files:read
