# HEAD /api/v4/projects/{id}/repository/files/{file_path}

**Resource:** [Files](../resources/Files.md)
**Get file metadata from repository**
**Operation ID:** `headApiV4ProjectsIdRepositoryFilesFilePath`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `file_path` | path | string | Yes | The URL-encoded path to the file. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

