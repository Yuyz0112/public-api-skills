# POST /api/v4/projects/{id}/repository/files/{file_path}/authorize

**Resource:** [Files](../resources/Files.md)
**Authorize create files upload**
**Operation ID:** `postApiV4ProjectsIdRepositoryFilesFilePathAuthorize`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

