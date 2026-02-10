# GET /api/v4/projects/{id}/repository/files/{file_path}

**Resource:** [Files](../resources/Files.md)
**Get a file from the repository**
**Operation ID:** `getApiV4ProjectsIdRepositoryFilesFilePath`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `file_path` | path | string | Yes | The URL-encoded path to the file. |
| `ref` | query | string | Yes | The name of branch, tag or commit |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

