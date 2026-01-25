# GET /v1/files/{file_key}/dev_resources

**Resource:** [Dev Resources](../resources/Dev-Resources.md)
**Get dev resources**
**Operation ID:** `getDevResources`

Get dev resources in a file

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | The file to get the dev resources from. This must be a main file key, not a branch key. |
| `node_ids` | query | string | No | Comma separated list of nodes that you care about in the document. If specified, only dev resources attached to these nodes will be returned. If not specified, all dev resources in the file will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_dev_resources:read
