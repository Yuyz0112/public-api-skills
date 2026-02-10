# GET /api/v4/snippets/{id}/files/{ref}/{file_path}/raw

**Resource:** [Snippets](../resources/Snippets.md)
**Get raw snippet file contents from the repository**
**Operation ID:** `getApiV4SnippetsIdFilesRefFilePathRaw`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_path` | path | string | Yes | The URL-encoded path to the file, like lib%2Fclass%2Erb |
| `ref` | path | string | Yes | The name of branch, tag or commit |

## Responses

| Status | Description |
|--------|-------------|
| 404 | Not found |

