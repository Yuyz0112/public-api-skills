# GET /api/v4/projects/{id}/repository/files/{file_path}/blame

**Resource:** [Files](../resources/Files.md)
**Get blame file from the repository**
**Operation ID:** `getApiV4ProjectsIdRepositoryFilesFilePathBlame`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `file_path` | path | string | Yes | The URL-encoded path to the file. |
| `ref` | query | string | Yes | The name of branch, tag or commit |
| `range` | query | object | No | Object that contains the blame range |
| `range[start]` | query | integer | Yes | The first line of the range to blame |
| `range[end]` | query | integer | Yes | The last line of the range to blame |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBlameRange](../schemas/APIEntitiesBlameRange/APIEntitiesBlameRange.md)

