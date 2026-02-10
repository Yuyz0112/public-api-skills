# GET /api/v4/projects/{id}/repository/files/{file_path}/raw

**Resource:** [Files](../resources/Files.md)
**Get raw file contents from the repository**
**Operation ID:** `getApiV4ProjectsIdRepositoryFilesFilePathRaw`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `file_path` | path | string | Yes | The URL-encoded path to the file. |
| `ref` | query | string | No | The name of branch, tag or commit |
| `lfs` | query | boolean | No | Retrieve binary data for a file that is an lfs pointer |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

